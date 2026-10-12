<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wh6_ypbne"/><circle class="roa3hckgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sheriff-star-sharp" /></template>
<style>
.roa3hckgy {
  cx: 12px;
  cy: 12.75px;
  r: 1.35px;
}

.wh6_ypbne {
  d: path("M11.43 6.48a1.35 1.35 0 1 1 1.14 0l1.55 3.36l3.67.43a1.35 1.35 0 1 1 .35 1.08l-2.72 2.51l.73 3.63a1.35 1.35 0 1 1-.92.67L12 16.35l-3.23 1.81a1.35 1.35 0 1 1-.92-.67l.73-3.63l-2.72-2.51a1.35 1.35 0 1 1 .35-1.08l3.67-.43Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
