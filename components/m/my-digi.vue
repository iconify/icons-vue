<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="xded_3moq"/><rect transform="matrix(-1 0 0 -1 45.82 58.157)" class="actz7ubnp"/><path class="h4iry67zr"/><path class="bfgwd-ogj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-digi" /></template>
<style>
.actz7ubnp {
  width: 5.069px;
  height: 6.717px;
  x: 20.375px;
  y: 25.72px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.535px;
  ry: 2.535px;
}

.bfgwd-ogj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.002 14.84v3.3a2 2 0 1 1-4 0v-3.3m-2.198 10.88v6.717m10.233-6.717v6.717m-13.005-4.182a2.535 2.535 0 1 0-5.07 0v1.648a2.535 2.535 0 0 0 5.07 0m0 2.534V22.298");
}

.h4iry67zr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.002 18.14v2.7a2 2 0 0 1-2 2a2 2 0 0 1-1.414-.585");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

.xded_3moq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.963 20.132v-7.991l4 8l4-7.988v7.988m7.481 5.579v7.604a2.535 2.535 0 0 1-4.327 1.793");
}

</style>
