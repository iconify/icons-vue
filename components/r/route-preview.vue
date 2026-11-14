<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jk9vx52lc"/><path class="chz4l4b8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-preview" /></template>
<style>
.chz4l4b8j {
  d: path("M5 16v-6a3 3 0 0 1 3-3h7.5m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM14 18.5q4-5 8 0q-4 5-8 0Z");
}

.jk9vx52lc {
  d: path("M2.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
