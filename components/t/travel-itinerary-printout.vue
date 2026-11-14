<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7oxhnbuw"/><path class="m5ro8fbbx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-itinerary-printout" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7oxhnbuw {
  d: path("M7.5 9h9a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 13.5v-1A3.5 3.5 0 0 1 7.5 9m0 0V3.5h9V9");
}

.m5ro8fbbx {
  d: path("M9 14h6a1.5 1.5 0 0 1 1.5 1.5V19a1.5 1.5 0 0 1-1.5 1.5H9A1.5 1.5 0 0 1 7.5 19v-3.5A1.5 1.5 0 0 1 9 14m1 3h4.5");
}

</style>
