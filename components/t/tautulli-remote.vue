<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="c280_ctrz"/><circle class="cx9ao4oyp"/><circle class="bfp3bcbvr"/><circle class="bfhrwfboq"/><path class="id2q7bx6i"/><circle class="vafz7bbga"/><path class="xjau5u6bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tautulli-remote" /></template>
<style>
.bfhrwfboq {
  cx: 9.736px;
  cy: 38.264px;
  r: 4.236px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.bfp3bcbvr {
  cx: 9.736px;
  cy: 19.702px;
  r: 4.236px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.c280_ctrz {
  cx: 38.264px;
  cy: 38.264px;
  r: 4.236px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.cx9ao4oyp {
  cx: 38.264px;
  cy: 9.736px;
  r: 4.236px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.id2q7bx6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.052 32.783c-1.495 1.62-3.986 1.744-5.73.374l-.374-.374c0 .124-.125.124-.125.249c-1.495 1.744-1.246 4.485.623 5.98c1.744 1.495 4.485 1.246 5.98-.623c1.246-1.62 1.121-4.111-.374-5.606");
}

.vafz7bbga {
  cx: 24.062px;
  cy: 29.918px;
  r: 4.236px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xjau5u6bx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.476 22.941l7.475 8.347m15.946-18.064L26.678 26.18m-6.353 5.731l-6.603 4.111m14.825.623l5.482.623");
}

</style>
