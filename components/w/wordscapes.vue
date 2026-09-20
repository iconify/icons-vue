<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jh4-4yemr"/><circle class="xixou6bds"/><circle class="qbw8wb5uf"/><circle class="iytb3fexm"/><circle class="f5rm04b1r"/><path class="roljy2aaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wordscapes" /></template>
<style>
.f5rm04b1r {
  cx: 29.203px;
  cy: 34.618px;
  r: 7.387px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iytb3fexm {
  cx: 12.887px;
  cy: 24.81px;
  r: 7.387px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jh4-4yemr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.282 38.588V31.2h1.662a3.23 3.23 0 0 1 3.232 3.231v.924a3.23 3.23 0 0 1-3.232 3.231zm7.185-14.403v-7.387h2.418c1.367 0 2.475 1.11 2.475 2.48s-1.108 2.481-2.475 2.481h-2.418m2.418 0l2.418 2.424M21.862 8.026za2.447 2.447 0 0 1 2.447 2.447v2.493a2.447 2.447 0 0 1-4.894 0v-2.493a2.447 2.447 0 0 1 2.447-2.447M16.183 21.23l-1.846 7.387l-1.847-7.387l-1.847 7.387l-1.847-7.387");
}

.qbw8wb5uf {
  cx: 36.498px;
  cy: 20.491px;
  r: 6.002px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.roljy2aaf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.841 25.873l-1.177 2.22m-1.17-10.916l-4.225-2.305m-9.176 1.68l-1.53 1.85");
}

.xixou6bds {
  cx: 22.001px;
  cy: 11.997px;
  r: 6.002px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
