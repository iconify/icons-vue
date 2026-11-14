<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcsy5exqr"/><path class="p2lwlybmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pancreas" /></template>
<style>
.hcsy5exqr {
  d: path("M3.5 13c0-3.5 2.25-5.5 5-5c2.5.5 4 2 6.5 1.75l4.5-1c1.25-.25 2 .5 1.5 1.5c-.75 1.5-3.5 2.5-6.5 4.25c-2.5 1.5-4 4.5-7 4.5c-2.5 0-4-2.5-4-6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2lwlybmi {
  d: path("M6.5 14c3-.5 6.5-1.5 11-3");
}

</style>
