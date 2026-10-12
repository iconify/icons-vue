<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mijjdfbkf"/><circle class="d3dnky5lg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quarter-note-sharp" /></template>
<style>
.d3dnky5lg {
  cx: 18.25px;
  cy: 10px;
  r: 1.25px;
}

.mijjdfbkf {
  d: path("M8.24 7.87a4 2.9-20 1 0 7.52-2.74a4 2.9-20 1 0-7.52 2.74ZM8.4 7v14.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
