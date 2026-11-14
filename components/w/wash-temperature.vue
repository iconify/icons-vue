<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vm8ox1new"/><path class="qyrqs1bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wash-temperature" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qyrqs1bmk {
  d: path("M16 9.5q2.5 1.5 5 0m-10.25 3V4.25a1.25 1.25 0 0 1 2.5 0v8.25a2.75 2.75 0 1 1-2.5 0");
}

.vm8ox1new {
  d: path("m3 9.5l2.25 11h13.5L21 9.5m-18 0q2.5-1.5 5 0");
}

</style>
