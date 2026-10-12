<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="y3ta-w_yv"/><path class="z6hf7-b6q"/><path class="e-lazibut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sentiment-analysis-sharp" /></template>
<style>
.e-lazibut {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.25 10.25l2 2.182l2-2.182m3.75 8.5v2.5m3-5v5m3-7.5v7.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y3ta-w_yv {
  cx: 8.25px;
  cy: 8.25px;
  r: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z6hf7-b6q {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.25h.01m3.49 0h.01");
}

</style>
