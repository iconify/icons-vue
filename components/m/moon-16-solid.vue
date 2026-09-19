<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj_w5bbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dj_w5bbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:moon-16-solid" /></template>
