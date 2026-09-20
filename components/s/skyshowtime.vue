<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="i-ph_l8vd"/><path class="xh6uxvvhz"/><rect class="gd42y4bwt"/><path class="m454abcag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skyshowtime" /></template>
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

.gd42y4bwt {
  width: 3.975px;
  height: 9.245px;
  x: 37.679px;
  y: 19.077px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.988px;
  ry: 1.988px;
}

.i-ph_l8vd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.2 25.72v2.99a2.214 2.214 0 0 1-2.214 2.213a2.2 2.2 0 0 1-1.566-.648");
}

.m454abcag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.772 27.511c.453.59 1.022.81 1.813.81h.17a1.845 1.845 0 0 0 1.846-1.844v-.933a1.845 1.845 0 0 0-1.845-1.845h-.284a1.847 1.847 0 0 1-1.847-1.847v-.924a1.85 1.85 0 0 1 1.851-1.851h.165c.79 0 1.36.22 1.813.81m5.626-4.065c-2.512-3.395-6.533-5.607-11.08-5.607s-8.568 2.212-11.08 5.607m0 16.356c2.512 3.395 6.533 5.607 11.08 5.607s8.568-2.212 11.08-5.607");
}

.xh6uxvvhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.2 22.066v3.654a2.214 2.214 0 0 1-4.429 0v-3.654m-6.289-2.989v8.857m4.429-.013l-3.152-3.138l2.733-2.72M6.485 27.439c.404.34.841.495 1.821.495h.497c.809 0 1.464-.657 1.464-1.467S9.612 25 8.803 25H7.81a1.465 1.465 0 0 1-1.464-1.467c0-.81.655-1.467 1.464-1.467h.496c.98 0 1.417.156 1.822.495m21.524-3.484v9.245m3.975-9.245v9.245m-3.975-4.64h3.975");
}

</style>
