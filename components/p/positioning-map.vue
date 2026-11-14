<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_q_y1bdx"/><path class="jm6szfg0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:positioning-map" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.jm6szfg0s {
  d: path("M8 8.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m7.5-2a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-5 7.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m6 1a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
