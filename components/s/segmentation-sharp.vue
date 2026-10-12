<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><path class="m8gr1ldps"/><circle class="e-ysxcb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:segmentation-sharp" /></template>
<style>
.e-ysxcb4m {
  cx: 15.75px;
  cy: 7.5px;
  r: 2.25px;
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.m8gr1ldps {
  d: path("M2.75 14.25c4.5-.25 7-3.5 7.25-11.5m-.25 18.5c.5-4.75 4.5-7.75 11.5-8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
