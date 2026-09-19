<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p2ohhh6pb"/><circle class="wgl-nsbjt"/><path class="r9wqyjbyh"/><circle class="xoq7lnb7k"/><circle class="enmjcab1x"/><circle class="kd48b73hq"/><circle class="xc1c0e7ou"/><path class="t4leakbym"/><circle class="g4y84hr3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:squeezer" /></template>
<style>
.enmjcab1x {
  cx: 20.041px;
  cy: 30.631px;
  r: 2.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g4y84hr3q {
  cx: 34.671px;
  cy: 12.273px;
  r: 0.75px;
  fill: currentColor;
}

.kd48b73hq {
  cx: 20.041px;
  cy: 18.772px;
  r: 2.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p2ohhh6pb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.067 17.808h13.688m3.106 5.81v9.963a1.85 1.85 0 0 1-1.639 1.66l-1.875-.009l-.002 5.71a2.061 2.061 0 0 1-4.123.009l.002-5.71H28.1l-.002 5.71a2.061 2.061 0 0 1-4.123.008l.003-5.71l-1.875.007a1.88 1.88 0 0 1-1.542-1.185a1.3 1.3 0 0 1-.098-.475");
}

.r9wqyjbyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.67 8.03l1.367-3.044m-11.93 0l1.366 3.044");
}

.t4leakbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.517 15.869a9.7 9.7 0 0 1 19.309.168m-26.373 3.691a7.834 7.834 0 0 0-.027 10.01h.027M8.022 14.95a15.404 15.404 0 0 0 0 19.605");
}

.wgl-nsbjt {
  cx: 25.564px;
  cy: 12.273px;
  r: 0.75px;
  fill: currentColor;
}

.xc1c0e7ou {
  cx: 39.891px;
  cy: 19.801px;
  r: 3.609px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xoq7lnb7k {
  cx: 20.041px;
  cy: 24.753px;
  r: 2.784px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
