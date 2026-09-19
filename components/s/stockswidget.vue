<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkfg0nb1r"/><circle class="jlpa5f4yx"/><circle class="tmiq6rb0s"/><circle class="jxtdmm0mv"/><circle class="ga15g-b2j"/><path class="l79u2sbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stockswidget" /></template>
<style>
.bkfg0nb1r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5v35a2 2 0 0 0 2 2h35M5.5 36h3m-3-6h3m-3-6h3m-3-6h3m-3-6h3");
}

.ga15g-b2j {
  cx: 15.2px;
  cy: 33px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jlpa5f4yx {
  cx: 39px;
  cy: 12px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jxtdmm0mv {
  cx: 21.85px;
  cy: 18px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.l79u2sbdm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.62 29.8l3.81-8.6m9.88 2.04l-5.49-3.4m12.79-4.63l-2.88 6.69");
}

.tmiq6rb0s {
  cx: 33.28px;
  cy: 25.08px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
