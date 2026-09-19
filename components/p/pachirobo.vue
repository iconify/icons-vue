<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z38ul-b4j"/><ellipse class="pc0z3dvhh"/><ellipse class="h5e8bdbua"/><ellipse class="qzqzuxi0c"/><ellipse class="h848m3r5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pachirobo" /></template>
<style>
.h5e8bdbua {
  cx: 32.5px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.5px;
  ry: 11px;
}

.h848m3r5t {
  cx: 28px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 4.5px;
}

.pc0z3dvhh {
  cx: 15.5px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.5px;
  ry: 11px;
}

.qzqzuxi0c {
  cx: 20px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 4.5px;
}

.z38ul-b4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 11h39v26h-39z");
}

</style>
