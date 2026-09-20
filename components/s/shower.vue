<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="okw466bku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shower" /></template>
<style>
.okw466bku {
  fill: currentColor;
  d: path("M64 236a12 12 0 1 1-12-12a12 12 0 0 1 12 12m20-44a12 12 0 1 0 12 12a12 12 0 0 0-12-12m-64 0a12 12 0 1 0 12 12a12 12 0 0 0-12-12m32-32a12 12 0 1 0 12 12a12 12 0 0 0-12-12M256 40a8 8 0 0 1-8 8h-28.69l-27.85 27.86l-21.66 126.79a16 16 0 0 1-27.09 8.66l-98-98a16 16 0 0 1 8.69-27.1l126.74-21.67l30.2-30.2A8 8 0 0 1 216 32h32a8 8 0 0 1 8 8m-81.79 41.79L56 102l98 98Z");
}

</style>
