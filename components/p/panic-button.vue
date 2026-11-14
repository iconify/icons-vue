<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkl72kbds"/><path class="p-_d3zbei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:panic-button" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nkl72kbds {
  d: path("M5 12a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

.p-_d3zbei {
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0M5 5L3.75 3.75M19 5l1.25-1.25M5 19l-1.25 1.25M19 19l1.25 1.25");
}

</style>
