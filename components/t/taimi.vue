<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y44z3fe2k"/><path class="m-8wv7bzh"/><circle class="fgfl_-skm"/><path class="oz9z10brg"/><circle class="p4bgvf0bb"/><path class="ib-oztsni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:taimi" /></template>
<style>
.fgfl_-skm {
  cx: 22.991px;
  cy: 20.335px;
  r: 0.75px;
  fill: currentColor;
}

.ib-oztsni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.65 22.885v5.63M26.178 25.01a2.13 2.13 0 0 1 2.124-2.125h0a2.13 2.13 0 0 1 2.125 2.124v3.4m-4.249-5.524v5.523m4.249-3.398a2.13 2.13 0 0 1 2.124-2.125h0a2.13 2.13 0 0 1 2.125 2.124v3.4");
}

.m-8wv7bzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.804 26.39a2.13 2.13 0 0 1-2.124 2.125h0a2.13 2.13 0 0 1-2.125-2.125v-1.38a2.13 2.13 0 0 1 2.124-2.125h0a2.13 2.13 0 0 1 2.125 2.124m0 3.506v-5.63");
}

.oz9z10brg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.991 22.885v5.63");
}

.p4bgvf0bb {
  cx: 37.65px;
  cy: 20.335px;
  r: 0.75px;
  fill: currentColor;
}

.y44z3fe2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m-29 14.517h5.63m-2.762 8.498v-8.498");
}

</style>
