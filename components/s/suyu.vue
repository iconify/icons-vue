<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="nbvmnac2z"/><circle class="vfamcob_x"/><circle class="nyo585fee"/><circle class="e8tbdvb5k"/><circle class="pv3x00bbg"/><circle class="m28qi8y2y"/><circle class="e7id8yd2s"/><circle class="wox2kis-x"/><circle class="e11prvb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:suyu" /></template>
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

.e11prvb9a {
  cx: 27.75px;
  cy: 34.75px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e7id8yd2s {
  cx: 24px;
  cy: 38.5px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e8tbdvb5k {
  cx: 20.25px;
  cy: 13.25px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m28qi8y2y {
  cx: 20.25px;
  cy: 34.75px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nbvmnac2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c-5.937 0-10.75 4.813-10.75 10.75S18.063 24 24 24s10.75 4.813 10.75 10.75S29.937 45.5 24 45.5");
}

.nyo585fee {
  cx: 27.75px;
  cy: 13.25px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pv3x00bbg {
  cx: 24px;
  cy: 17px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vfamcob_x {
  cx: 24px;
  cy: 9.5px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wox2kis-x {
  cx: 24px;
  cy: 31px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
