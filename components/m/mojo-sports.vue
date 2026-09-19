<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m5_hr7brb"/><circle class="dqwm3zv7q"/><path class="rayn8_9qc"/><circle class="vtwsnj8by"/><circle class="u_jhden4o"/><path class="jijzeti_k"/><path class="po-q0-bdg"/><path class="tujlvm-0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mojo-sports" /></template>
<style>
.dqwm3zv7q {
  cx: 39.77px;
  cy: 35.189px;
  r: 3.729px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jijzeti_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.418 31.46a7.46 7.46 0 1 1-14.918 0h7.46V24h7.458z");
}

.m5_hr7brb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.77 33.324v3.729m-1.614-2.797l3.229 1.865m-3.229 0l3.229-1.865");
}

.po-q0-bdg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.915 37.73a30.5 30.5 0 0 1 11.506-7.132c.019-.01.028-.01.047-.018a30.5 30.5 0 0 1 9.846-1.623a30 30 0 0 1 4.717.364");
}

.rayn8_9qc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.418 24H4.5V9.082l7.459 7.459l7.459-7.459z");
}

.tujlvm-0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.42 38.423a24.6 24.6 0 0 1 9.464-5.414c.015-.007.023-.007.038-.014c2.514-.76 5.2-1.025 7.972-1.025c2.337 0 4.502.423 7.257 1.147");
}

.u_jhden4o {
  cx: 26.877px;
  cy: 31.459px;
  r: 7.459px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vtwsnj8by {
  cx: 26.877px;
  cy: 16.541px;
  r: 7.459px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
