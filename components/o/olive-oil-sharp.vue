<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jdza8lbnn"/><circle class="mlqk6dbfd"/><path class="qwnhnjb-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:olive-oil-sharp" /></template>
<style>
.jdza8lbnn {
  d: path("M8.25 2.75h3.5v3.5l2 2.75v12.25h-7.5V9l2-2.75Zm0 2.25h3.5");
}

.mlqk6dbfd {
  cx: 18px;
  cy: 18px;
  r: 2.75px;
}

.qwnhnjb-x {
  d: path("M18 15.25V13l2.25-.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
