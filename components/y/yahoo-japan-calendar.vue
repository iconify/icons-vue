<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="c434vbbyi"/><path class="oeu_iccny"/><path class="mpf-2jkda"/><rect class="algh-eb6f"/><rect class="sq_w7razy"/><path class="exmdi8t_n"/><rect class="j3s9ivbxi"/><path class="ew82gubmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yahoo-japan-calendar" /></template>
<style>
.algh-eb6f {
  width: 3px;
  height: 6px;
  x: 13.25px;
  y: 10.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.5px;
  ry: 0.5px;
}

.c434vbbyi {
  width: 28.25px;
  height: 16.95px;
  x: 9.875px;
  y: 20.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.5px;
  ry: 0.5px;
}

.ew82gubmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 13.75h-7.75m-3 0h-15.5m-3 0H5.5");
}

.exmdi8t_n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.825 20.65h5.65V37.6h-5.65z");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mpf-2jkda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.525 20.65h5.65V37.6h-5.65z");
}

.oeu_iccny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.875 26.3h28.25v5.65H9.875z");
}

.sq_w7razy {
  width: 3px;
  height: 6px;
  x: 31.75px;
  y: 10.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.5px;
  ry: 0.5px;
}

</style>
