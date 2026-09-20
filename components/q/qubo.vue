<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nqgnfjube"/><circle class="sq363xb3s"/><circle class="h_u7t_hpf"/><circle class="v253bqifj"/><circle class="iwj34baar"/><path class="qtrb3ibvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qubo" /></template>
<style>
.h_u7t_hpf {
  cx: 30.5px;
  cy: 30.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.iwj34baar {
  cx: 30.5px;
  cy: 8px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nqgnfjube {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 18.5h13c6.627 0 12 5.373 12 12s-5.373 12-12 12h-13c-6.627 0-12-5.373-12-12s5.373-12 12-12");
}

.qtrb3ibvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 10.5v8m13-8v8");
}

.sq363xb3s {
  cx: 17.5px;
  cy: 30.5px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v253bqifj {
  cx: 17.5px;
  cy: 8px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
