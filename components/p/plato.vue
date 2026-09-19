<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d_hw75bjg"/><path class="ly7-yebrm"/><ellipse class="hgivi1wir"/><ellipse class="i2e0dui0l"/><ellipse class="kqp5m6bmh"/><ellipse transform="rotate(-36.149 18.919 27.762)" class="g94ybkoie"/><ellipse transform="rotate(-36.149 12.263 23.513)" class="o8kvau3nq"/><ellipse transform="rotate(-53.851 28.479 27.762)" class="d91nozboc"/><ellipse transform="rotate(-53.851 35.134 23.513)" class="nqdyvybgw"/><ellipse transform="rotate(-36.149 18.919 34.26)" class="om_c_zt_q"/><ellipse transform="rotate(-36.149 12.263 30.012)" class="mvloojbyb"/><path class="blt0j4byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plato" /></template>
<style>
.blt0j4byg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.654 33.308c2.86 1.136 5.766-.495 7.628-4.421");
}

.d_hw75bjg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m40.9 14.273l-.055 19.454L24.027 43.5l.056-19.453m0 0L24.027 43.5L7.1 33.727l.055-19.454z");
}

.d91nozboc {
  cx: 28.479px;
  cy: 27.762px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.307px;
  ry: 1.231px;
}

.g94ybkoie {
  cx: 18.919px;
  cy: 27.762px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.231px;
  ry: 2.307px;
}

.hgivi1wir {
  cx: 24.028px;
  cy: 14.273px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.219px;
  ry: 1.147px;
}

.i2e0dui0l {
  cx: 30.683px;
  cy: 14.273px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.219px;
  ry: 1.147px;
}

.kqp5m6bmh {
  cx: 17.372px;
  cy: 14.273px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.219px;
  ry: 1.147px;
}

.ly7-yebrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.791 18.986l8.109-4.713L23.973 4.5L7.155 14.273l16.927 9.774l4.83-2.807l2.493 1.503z");
}

.mvloojbyb {
  cx: 12.263px;
  cy: 30.012px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.231px;
  ry: 2.307px;
}

.nqdyvybgw {
  cx: 35.134px;
  cy: 23.513px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.307px;
  ry: 1.231px;
}

.o8kvau3nq {
  cx: 12.263px;
  cy: 23.513px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.231px;
  ry: 2.307px;
}

.om_c_zt_q {
  cx: 18.919px;
  cy: 34.261px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.231px;
  ry: 2.307px;
}

</style>
