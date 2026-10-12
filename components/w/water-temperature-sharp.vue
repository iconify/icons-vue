<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="alpotnr_d"/><circle class="zur2nlbbt"/><path class="kk6g3bbbu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-temperature-sharp" /></template>
<style>
.alpotnr_d {
  d: path("M9.5 8.7V5.25a2.5 2.5 0 0 1 5 0V8.7a3.75 3.75 0 1 1-5 0Zm2.5 1.8V6");
}

.kk6g3bbbu {
  d: path("M2.75 20.5c1.54 0 1.54-1 3.08-1s1.55 1 3.09 1s1.54-1 3.08-1s1.54 1 3.08 1s1.55-1 3.09-1s1.54 1 3.08 1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zur2nlbbt {
  cx: 12px;
  cy: 11.5px;
  r: 1.25px;
}

</style>
