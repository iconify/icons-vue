<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="qz57lhbjs"/><path class="jaz6-diah"/><rect class="eo_osutqe"/><path class="wcy6gw5va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:neato" /></template>
<style>
.eo_osutqe {
  width: 4.697px;
  height: 6.106px;
  x: 34.15px;
  y: 20.494px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.349px;
  ry: 2.349px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jaz6-diah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.706 22.701V26.6m-7.613-.688a2.34 2.34 0 0 1-1.661.688h-.001a2.35 2.35 0 0 1-2.35-2.35v-1.549a2.35 2.35 0 0 1 2.35-2.349h0a2.35 2.35 0 0 1 2.35 2.35v.703m0 .071h-4.7");
}

.qz57lhbjs {
  width: 4.697px;
  height: 6.248px;
  x: 23.009px;
  y: 20.352px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.349px;
  ry: 2.349px;
}

.wcy6gw5va {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.153 22.842a2.35 2.35 0 0 1 2.349-2.348h0a2.35 2.35 0 0 1 2.348 2.348V26.6m-4.697-3.758V26.6m22.054-9.394V26.6m-1.227-6.106h1.227m0 0h1.228");
}

</style>
