<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mj2n4sbvj"/><circle class="be00zvkmw"/><path class="ds7xew7dq"/><circle class="u1k2o1bqq"/><circle class="ho87c4jkp"/><circle class="byfrixb5k"/><circle class="aruqljb2b"/><circle class="sjimo_bxv"/><circle class="au8c_1byc"/><path class="rbe7e734b"/><path class="y3n065bea"/><rect class="xyv480frc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omw" /></template>
<style>
.aruqljb2b {
  cx: 40.64px;
  cy: 17.4px;
  r: 0.71px;
  fill: currentColor;
}

.au8c_1byc {
  cx: 40.64px;
  cy: 24.6px;
  r: 0.71px;
  fill: currentColor;
}

.be00zvkmw {
  cx: 40.64px;
  cy: 13.8px;
  r: 0.72px;
  fill: currentColor;
}

.byfrixb5k {
  cx: 37.04px;
  cy: 24.7px;
  r: 0.72px;
  fill: currentColor;
}

.ds7xew7dq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.3 39.1H14l.9-2.3H9.4Zm23.7 0h3.7l.9-2.3H33Z");
}

.ho87c4jkp {
  cx: 37.04px;
  cy: 21.1px;
  r: 0.75px;
  fill: currentColor;
}

.mj2n4sbvj {
  cx: 37.04px;
  cy: 13.8px;
  r: 0.75px;
  fill: currentColor;
}

.rbe7e734b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.56 12.8V17l-2 2.8v6.3l2 2.3v4.3");
}

.sjimo_bxv {
  cx: 40.64px;
  cy: 21px;
  r: 0.71px;
  fill: currentColor;
}

.u1k2o1bqq {
  cx: 37.04px;
  cy: 17.4px;
  r: 0.75px;
  fill: currentColor;
}

.xyv480frc {
  width: 39px;
  height: 27.9px;
  x: 4.5px;
  y: 8.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.y3n065bea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.2 12.8h26.2v19.9H8.2zm28.59 17h4.1v3h-4.1z");
}

</style>
