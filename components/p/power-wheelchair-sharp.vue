<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="c20mdzq7v"/><path class="ard1fccgb"/><path class="ga265t4ra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-wheelchair-sharp" /></template>
<style>
.ard1fccgb {
  d: path("M10.5 8.5v4.75h5.25l2 5.25h2.5m-9.75-8.25h4");
}

.c20mdzq7v {
  cx: 11px;
  cy: 4.5px;
  r: 1.5px;
}

.ga265t4ra {
  d: path("M8.38 11.33a5 5 0 1 0 5.79 4.05M18 9h3v2.5h-3zm1.5 0V7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
