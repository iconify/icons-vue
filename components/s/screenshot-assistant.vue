<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="fc7r1tbjr"/><path class="hsnrrqbve"/><circle class="y3ve1hbby"/><path class="nsla2fcqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screenshot-assistant" /></template>
<style>
.fc7r1tbjr {
  width: 24px;
  height: 39px;
  x: 11.999px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

.hsnrrqbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.09 10.538h18v27h-18z");
}

.nsla2fcqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.907 25.565l.907-1.571l-.907-1.57h-1.814l-.907 1.57l.907 1.571zm.907-1.571l2.442 4.23m-8.512-8.459l2.442 4.229m3.349-5.8l-2.442 4.229m1.814 3.142l-2.442 4.23m.628-4.23h-4.885m6.699-3.142h4.885");
}

.y3ve1hbby {
  cx: 24px;
  cy: 23.994px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
