<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><rect class="h4-t3ccay"/><path class="f0w8sgbjp"/><path class="c1djodbgq"/><circle class="twgttab6r"/><circle class="r19pk5obe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:survivor-io" /></template>
<style>
.c1djodbgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.619 13.668l4.085.626a.94.94 0 0 1 .798.93v2.843a.94.94 0 0 1-.798.93l-4.93.756");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f0w8sgbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.984 19.321v9.731h18.63v-9.176M10.22 40.503v-10.21c0-.69.55-1.24 1.24-1.24h23.97c.69 0 1.24.55 1.24 1.24v11.074m-1.18-14.834h1.87c1.48 0 2.67 1.19 2.67 2.67v9.12m-4.57-19.29q.03.36.03.72v9.3m-19.47-17.24c1.14-.84 2.4-1.31 4.16-1.31h8.58c2.07 0 4.12 1.25 5.39 3.55");
}

.h4-t3ccay {
  width: 21.701px;
  height: 8.916px;
  x: 10.764px;
  y: 11.809px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.458px;
  ry: 4.458px;
}

.r19pk5obe {
  cx: 25.571px;
  cy: 24.314px;
  r: 1.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.twgttab6r {
  cx: 15.797px;
  cy: 24.314px;
  r: 1.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
