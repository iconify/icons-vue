<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ir4kmqb-k"/><circle class="rmojggbbz"/><circle class="dcgw77bis"/><circle class="oi0ahrvvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soybean-sharp" /></template>
<style>
.dcgw77bis {
  cx: 12px;
  cy: 12px;
  r: 1.5px;
}

.ir4kmqb-k {
  d: path("m3.39 18.49l-.11-2.01l-.12-2l1.41-1.41l8.5-8.5l1.41-1.41l2 .12l2.01.11l2 .12l.12 2l.11 2.01l.12 2l-1.41 1.41l-8.5 8.5l-1.41 1.41l-2-.12l-2.01-.11l-2-.12z");
}

.oi0ahrvvo {
  cx: 16.42px;
  cy: 7.58px;
  r: 1.5px;
}

.rmojggbbz {
  cx: 7.58px;
  cy: 16.42px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
