<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q48no5bch"/><rect class="j3s9ivbxi"/><circle class="jhfablb8c"/><path class="rxi3h_bfo"/><circle class="j3m1x2bkm"/><circle class="zpf40_osg"/><path class="v7ewlokwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:math-ai" /></template>
<style>
.j3m1x2bkm {
  cx: 14.75px;
  cy: 37.888px;
  r: 0.75px;
  fill: currentColor;
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

.jhfablb8c {
  cx: 37.473px;
  cy: 29.5px;
  r: 0.75px;
  fill: currentColor;
}

.q48no5bch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 20c0 2.216-1.784 4-4 4H28c-2.216 0-4 1.784-4 4v10.5c0 2.216-1.784 4-4 4");
}

.rxi3h_bfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.473 31.95v5.3m-4.224-2.65h-3.544m-.878 2.65l2.65-8l2.65 8");
}

.v7ewlokwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 33.25h9.5m10.05-22.2l7.4 7.4m0-7.4l-7.4 7.4m-18.675-3.7h7.75m-3.875-3.875v7.75");
}

.zpf40_osg {
  cx: 14.75px;
  cy: 28.612px;
  r: 0.75px;
  fill: currentColor;
}

</style>
