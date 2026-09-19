<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bk9uc-b8u"/><circle class="c-anc77zv"/><path class="e95a-sbzo"/><path class="f6ec74ixx"/><path class="qprdzwbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:uae4all2" /></template>
<style>
.bk9uc-b8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 19.75l4.57 6.66L21 8.58m-8.52 16.2l1.12 1.63L25.52 8.58M9 19.75l1.12 1.63m-.46 17.99l12.03-18.48m0 18.53V20.89m0 12.33h-8.03");
}

.c-anc77zv {
  cx: 33.97px;
  cy: 21.89px;
  r: 9.53px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e95a-sbzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.89 13.83a22 22 0 0 0 13.55 3.7M26 16.65a24 24 0 0 0 17.5 4.89m-18.94-1.18c4.08 3.23 12.34 7.11 18.37 4.79m-18.2-.89c4.72 3.87 10.61 5.65 16 4.38");
}

.f6ec74ixx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.28 12.45c-7.79 2.65-10.9 12.49-7.59 16.6m8.77-16.37a55.1 55.1 0 0 1-4.52 18.52m5.22-18.29c4.14 6.47.91 15.41-2.81 18.5");
}

.qprdzwbba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.77 13.15c4.24 4.41 6.46 11.31-.14 17.54M36.1 12.6c-5.64 4.39-8.5 14.94-6 18");
}

</style>
