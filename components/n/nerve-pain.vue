<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h6niiz0up"/><path class="u_630jbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nerve-pain" /></template>
<style>
.h6niiz0up {
  d: path("M2.5 16c2.5 0 3.5-2.5 6-2.5q.31.001.59.097m1.491 1.163c1.236 1.481 2.239 3.74 3.919 3.74c2.5 0 3.5-3 7-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u_630jbmu {
  fill: currentColor;
  d: path("m12.348 3.371l-2.074 4.494A.8.8 0 0 0 11 9a.955.955 0 0 1 .921 1.206L11.5 11.75a.428.428 0 0 0 .775.342l2.556-4.036A.688.688 0 0 0 14.25 7a.855.855 0 0 1-.797-1.165l.935-2.403a.684.684 0 0 0-.638-.932h-.04a1.5 1.5 0 0 0-1.362.871");
}

</style>
