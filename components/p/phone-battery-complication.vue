<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wn9edfbhg"/><path class="adiarg83f"/><rect class="qoj21dcyz"/><path class="lu65bmbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:phone-battery-complication" /></template>
<style>
.adiarg83f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.432 12.453l-1.31-5.674A2.94 2.94 0 0 0 28.256 4.5h-8.513a2.94 2.94 0 0 0-2.865 2.279l-1.31 5.67m0 23.099l1.31 5.673a2.94 2.94 0 0 0 2.865 2.279h8.513a2.94 2.94 0 0 0 2.865-2.279l1.31-5.674");
}

.lu65bmbwh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 29H19m0-10h10");
}

.qoj21dcyz {
  width: 10px;
  height: 16px;
  x: 19px;
  y: 16px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.wn9edfbhg {
  cx: 24px;
  cy: 24px;
  r: 14.3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
