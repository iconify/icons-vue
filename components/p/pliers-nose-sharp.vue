<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ipeesrb1t"/><circle class="adcsmfg4s"/><path class="e78eaab8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pliers-nose-sharp" /></template>
<style>
.adcsmfg4s {
  cx: 12px;
  cy: 11.75px;
  r: 2px;
}

.e78eaab8f {
  d: path("M10.25 13.25Q7 16 3.75 21.25H8L9.25 17l2.25-3.25Zm3.5 0q3.25 2.75 6.5 8H16L14.75 17l-2.25-3.25Z");
}

.ipeesrb1t {
  d: path("M9.75 10.5L12 2.75l2.25 7.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
