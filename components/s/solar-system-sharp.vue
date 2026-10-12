<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="ons53cb4g"/><path class="nfgvosgrx"/><circle class="ds98_ox3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:solar-system-sharp" /></template>
<style>
.ds98_ox3w {
  cx: 6.34px;
  cy: 6.34px;
  r: 1.5px;
}

.nfgvosgrx {
  d: path("M10.34 4.18a8 8 0 1 1-6.16 6.16");
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
