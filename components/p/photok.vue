<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="r2ou16beo"/><circle class="qfgf5wbmu"/><path class="ml2i9w9_k"/><rect class="zahvspw8p"/><path class="e69j_rb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photok" /></template>
<style>
.e69j_rb0m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.94 13.09h2.12v9.13H4.94a1 1 0 0 1-1-1v-7.13a1 1 0 0 1 1-1m0 12.7h2.12v9.13H4.94a1 1 0 0 1-1-1v-7.13a1 1 0 0 1 1-1");
}

.ml2i9w9_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.18 27.53a7.52 7.52 0 0 0 0-7.06l6.5-6.5a2.18 2.18 0 1 0-3.09-3.09l-6.51 6.5a7.5 7.5 0 0 0-7 0l-6.5-6.5A2.18 2.18 0 0 0 12.44 14l6.5 6.5a7.52 7.52 0 0 0 0 7.06L12.44 34a2.18 2.18 0 1 0 3.09 3.09l6.5-6.5a7.5 7.5 0 0 0 7 0l6.51 6.5A2.18 2.18 0 1 0 38.68 34Z");
}

.qfgf5wbmu {
  cx: 25.56px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.r2ou16beo {
  width: 37px;
  height: 37px;
  x: 7.06px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
}

.zahvspw8p {
  width: 3.31px;
  height: 8.27px;
  x: 37.98px;
  y: 19.86px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.65px;
}

</style>
