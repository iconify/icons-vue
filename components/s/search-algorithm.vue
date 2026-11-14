<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e0hu98b1s"/><path class="bgipqgbbz"/><path class="ittrhdb3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:search-algorithm" /></template>
<style>
.bgipqgbbz {
  fill: currentColor;
  d: path("M9.75 17.5h4.5v4h-4.5Z");
}

.e0hu98b1s {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm9.5 4l2.75 2.75M2.5 17.5H7v4H2.5Z");
}

.ittrhdb3u {
  d: path("M17 17.5h4.5v4H17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
