<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqu2my3vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xqu2my3vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mask" /></template>
