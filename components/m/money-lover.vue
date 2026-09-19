<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dza37f30r"/><circle class="wfzgdqbzb"/><circle class="unmk_7eiz"/><ellipse class="ecduukb6m"/><circle class="jvep7gy6c"/><circle class="x0nz91bgi"/><path class="f91dcmbin"/><path class="z2te6vqhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:money-lover" /></template>
<style>
.dza37f30r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.952a8 8 0 0 0 8 8h21a8 8 0 0 0 8-8");
}

.ecduukb6m {
  cx: 23.836px;
  cy: 35.957px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.686px;
  ry: 4.52px;
}

.f91dcmbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.883 21.913H33.48m-3.439 0a7.536 7.536 0 1 0-11.72 0z");
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

.jvep7gy6c {
  cx: 21.184px;
  cy: 35.797px;
  r: 0.967px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.unmk_7eiz {
  cx: 33.477px;
  cy: 31.774px;
  r: 1.804px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wfzgdqbzb {
  cx: 14.523px;
  cy: 31.774px;
  r: 1.804px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x0nz91bgi {
  cx: 26.841px;
  cy: 35.797px;
  r: 0.967px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z2te6vqhh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.623 11.39H24.41c-.765 1.727-2.147 3.082-3.842 3.743v.462h2.018v6.319h3.037z");
}

</style>
