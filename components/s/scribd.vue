<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="i8y1gmbtf"/><path class="ucrevacbk"/><circle class="ll6sr9bnr"/><path class="mpvbehv7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:scribd" /></template>
<style>
.i8y1gmbtf {
  cx: 15.895px;
  cy: 20.232px;
  r: 6.068px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ll6sr9bnr {
  cx: 32.105px;
  cy: 27.763px;
  r: 6.068px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mpvbehv7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.106 21.695c9.78 0 8.248 14.316 1.472 19.265s-18.214 2.167-24.214-4.055l2.533-3.594");
}

.ucrevacbk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.895 26.3c-9.78 0-8.249-14.316-1.473-19.265s15.023-1.885 21.68 2.651L33.57 13.28");
}

</style>
