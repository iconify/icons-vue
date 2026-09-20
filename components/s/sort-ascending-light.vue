<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kgnbp4m5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sort-ascending-light" /></template>
<style>
.kgnbp4m5e {
  fill: currentColor;
  d: path("M126 128a6 6 0 0 1-6 6H48a6 6 0 0 1 0-12h72a6 6 0 0 1 6 6M48 70h136a6 6 0 0 0 0-12H48a6 6 0 0 0 0 12m56 116H48a6 6 0 0 0 0 12h56a6 6 0 0 0 0-12m124.24-22.24a6 6 0 0 0-8.48 0L190 193.51V112a6 6 0 0 0-12 0v81.51l-29.76-29.75a6 6 0 0 0-8.48 8.48l40 40a6 6 0 0 0 8.48 0l40-40a6 6 0 0 0 0-8.48");
}

</style>
