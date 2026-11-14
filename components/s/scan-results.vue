<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lg5qn7b9d"/><path class="o3fg-cbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scan-results" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg5qn7b9d {
  d: path("M4 4.5c0-1.1.9-2 2-2h9l5 5v12c0 1.1-.9 2-2 2H6c-1.1 0-2-.9-2-2Z");
}

.o3fg-cbgw {
  d: path("M15 2.5v5h5m-13 2a3.5 3 0 1 0 7 0a3.5 3 0 1 0-7 0m3.5 0h.01M7 15.5h10m-10 3h7");
}

</style>
