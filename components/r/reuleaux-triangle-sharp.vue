<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="l5km3ey7j"/><path class="ikvuw6bzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reuleaux-triangle-sharp" /></template>
<style>
.ikvuw6bzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.25h.01");
}

.l5km3ey7j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.13 3.5L12 1.965l.87 1.535a15 15 0 0 1 6.53 12.1l.87 1.507l-1.74-.007a15 15 0 0 1-13.06 0l-1.74.007l.87-1.507a15 15 0 0 1 6.53-12.1Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
