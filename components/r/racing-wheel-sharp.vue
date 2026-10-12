<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zyrjm2b6x"/><circle class="yjztigbem"/><path class="vs_93njhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:racing-wheel-sharp" /></template>
<style>
.vs_93njhg {
  d: path("M5.25 12.5H10m4 0h4.75m-6.75 2v3m6.45-7h2.8v4h-2.8m-12.9-4h-2.8v4h2.8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjztigbem {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

.zyrjm2b6x {
  d: path("M7.47 17.5h9.06a6.75 6.75 0 1 0-9.06 0Z");
}

</style>
