<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o0x728vif"/><path class="w5datvb0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radon-sensor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o0x728vif {
  d: path("M7 16.25a5 5 0 1 0 10 0a5 5 0 1 0-10 0M8 8.5q1.25-1.5 0-3t0-3m4 6q1.25-1.5 0-3t0-3m4 6q1.25-1.5 0-3t0-3");
}

.w5datvb0q {
  d: path("M10.25 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
