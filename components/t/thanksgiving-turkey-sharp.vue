<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ibqgf5bfv"/><path class="ctbyz_v4b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thanksgiving-turkey-sharp" /></template>
<style>
.ctbyz_v4b {
  d: path("M10.6 11.25a2 2 0 1 1 2.8 0a4.25 4.5 0 1 1-2.8 0Zm.15 8.75v1.25m2.5-1.25v1.25");
}

.ibqgf5bfv {
  d: path("M7.17 11.71a2.75 2.75 0 0 1-3.86-1.04a2.75 2.75 0 0 1 3.86 1.04Zm1.29-2.25a2.75 2.75 0 0 1-2.82-2.82a2.75 2.75 0 0 1 2.82 2.82Zm2.25-1.29a2.75 2.75 0 0 1-1.04-3.86a2.75 2.75 0 0 1 1.04 3.86Zm2.58 0a2.75 2.75 0 0 1 1.04-3.86a2.75 2.75 0 0 1-1.04 3.86Zm2.25 1.29a2.75 2.75 0 0 1 2.82-2.82a2.75 2.75 0 0 1-2.82 2.82Zm1.29 2.25a2.75 2.75 0 0 1 3.86-1.04a2.75 2.75 0 0 1-3.86 1.04Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
