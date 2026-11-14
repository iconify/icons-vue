<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ntx1w0b7l"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:workout-history" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ntx1w0b7l {
  d: path("M4.5 4.5H8v12H4.5ZM16 12.3V4.5h3.5v7.6m-17-1.6h2m3.5 0h8m3.5 0h2M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
