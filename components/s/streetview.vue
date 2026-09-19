<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="pzvhfgbip"/><path class="hx_t56o6p"/><path class="qaxlxg12g"/><path class="nrs5xnbcn"/><path class="qpfh_2b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:streetview" /></template>
<style>
.hx_t56o6p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.3 19.5V39a2 2 0 0 1-2 2H10a2 2 0 0 1-2-2V9.7a2 2 0 0 1 2-2h19.4");
}

.nrs5xnbcn {
  fill: none;
  stroke: currentColor;
  d: path("m29.4 25.5l6.9 7l5-4.8M29.5 17.4L7.9 38.9m23.7-19.3L10 41.1");
}

.pzvhfgbip {
  cx: 36.4px;
  cy: 12.6px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qaxlxg12g {
  fill: none;
  stroke: currentColor;
  d: path("M25.2 41.1V29c1-3.6 10.3-6.4 16.2-4.3");
}

.qpfh_2b5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.2 15.8h4.9a4.87 4.87 0 0 1-4.9 5a5 5 0 0 1 0-10a4.3 4.3 0 0 1 2.5.7");
}

</style>
