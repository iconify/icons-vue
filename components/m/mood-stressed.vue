<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ohs_9v5no"/><path class="a4xninb_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mood-stressed" /></template>
<style>
.a4xninb_z {
  d: path("M8.25 16za1.35 1.35 0 0 1 1.5 0a1.35 1.35 0 0 0 1.5 0a1.35 1.35 0 0 1 1.5 0a1.35 1.35 0 0 0 1.5 0a1.35 1.35 0 0 1 1.5 0a.273.273 0 0 1-.151.5H8.401a.273.273 0 0 1-.151-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohs_9v5no {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0M7 7.75l3 1.5m7-1.5l-3 1.5M9 12h.01M15 12h.01");
}

</style>
