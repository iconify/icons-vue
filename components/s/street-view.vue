<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qfy0_x4-t"/><path class="e0erkbbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:street-view" /></template>
<style>
.e0erkbbcq {
  d: path("M7.5 15.5C4.5 16 3 16.9 3 18c0 1.75 4 3 9 3s9-1.25 9-3c0-1.1-1.5-2-4.5-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qfy0_x4-t {
  d: path("M10 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-.75 12.5v-5a2.75 2.75 0 0 1 5.5 0v5");
}

</style>
