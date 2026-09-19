<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="jkqdg1r5d"/><circle class="lak81ub3m"/><circle class="eo5xn3b2f"/><path class="os02pwbpm"/><path class="nprwlvn-f"/><path class="wy3t6yb_y"/><circle class="elkqebbyc"/><path class="bs1vukbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:net-analyzer" /></template>
<style>
.bs1vukbwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.149 16.948h3v3h-3zm-5.749.001V14.87h7.272v2.077m-3.647-3.669v1.593M24 2.5v43M45.5 24h-43m26.063 11.597l2.525 2.526l2.525-2.526m-2.525 2.495V30.38m7.576-.084l-2.525-2.525l-2.526 2.525m2.526-2.494v7.712");
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

.elkqebbyc {
  cx: 15.004px;
  cy: 32.947px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eo5xn3b2f {
  cx: 32.878px;
  cy: 15.201px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jkqdg1r5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.524 10.278h3v3h-3zm-3.625 6.67h3v3h-3z");
}

.lak81ub3m {
  cx: 32.878px;
  cy: 15.201px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nprwlvn-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.251 38.816a6 6 0 0 1-7.116-7.117M14 29.856a3.25 3.25 0 0 1 4.095 4.095");
}

.os02pwbpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.563 11.032l4.34 4.038l-4.233 4.409M16.169 35.98a3.25 3.25 0 0 1-4.238-4.091");
}

.wy3t6yb_y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.86 27.057a6 6 0 0 1 7.013 7.137");
}

</style>
