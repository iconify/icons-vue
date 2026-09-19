<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw1b57b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mw1b57b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:vimeo" /></template>
