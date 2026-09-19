<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_i8820zz"/><circle class="cpk0fnbgt"/><path class="kv5u6nbpq"/><path class="vhc60f4oh"/><path class="klhp88wic"/><circle class="lszdjb0ai"/><path class="csqxgz7-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbb-freesurf" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.csqxgz7-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.657v10.252");
}

.klhp88wic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.774 40.357a11.5 11.5 0 1 0-11.548 0");
}

.kv5u6nbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.421 15.318h39.158M25.848 33.592a3.68 3.68 0 1 0-3.696 0");
}

.lszdjb0ai {
  cx: 24px;
  cy: 30.409px;
  r: 1.249px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vhc60f4oh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.797 36.982a7.59 7.59 0 1 0-7.645-.03");
}

.z_i8820zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.87 6.041l2.865 2.868l-2.867 2.867m-5.739 0L18.265 8.91l2.867-2.868m-2.867 2.867h11.47M24 6.041v5.736");
}

</style>
