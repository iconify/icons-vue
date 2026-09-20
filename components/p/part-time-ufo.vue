<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="q7j9p2bhp"/><path class="yze6_sbub"/><path class="u-glv1brc"/><circle class="nd27jxb9w"/><path class="ltvnejbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:part-time-ufo" /></template>
<style>
.ltvnejbrh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.787 38.165a5.335 5.335 0 1 0 10.67 0m-24.551 0a5.335 5.335 0 0 0 9.652 3.135m5.974-28.829c-1.668 2.025-2.343 3.864-2.704 5.741");
}

.nd27jxb9w {
  cx: 30.552px;
  cy: 9.058px;
  r: 4.558px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q7j9p2bhp {
  width: 31.645px;
  height: 6.267px;
  x: 8.177px;
  y: 31.898px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.134px;
  ry: 3.134px;
}

.u-glv1brc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.942 31.898V25.04h1.917m-6.785 6.858V25.04h1.916");
}

.yze6_sbub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.804 41.299h-6.43a3.133 3.133 0 0 1-3.133-3.134m-4.351-6.267v-2.607c0-6.135 4.974-11.11 11.11-11.11s11.11 4.974 11.11 11.11v2.607");
}

</style>
