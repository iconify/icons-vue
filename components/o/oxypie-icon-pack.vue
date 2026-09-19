<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="n5e1s-bnj"/><path class="g4rzazhct"/><circle class="h9un3obtu"/><path class="t8p5qeflf"/><rect class="stl9v1b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oxypie-icon-pack" /></template>
<style>
.g4rzazhct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.77 21.847v2.93c0 .98-.795 1.776-1.776 1.776h0c-.98 0-1.776-.795-1.776-1.776v-2.93m-1.776 0l-3.552 4.706m3.552 0l-3.552-4.706");
}

.h9un3obtu {
  cx: 33.218px;
  cy: 19.671px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.n5e1s-bnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.668 26.553v-7.104h2.326c1.315 0 2.38 1.068 2.38 2.386s-1.065 2.386-2.38 2.386h-2.326m-1.898.556v2.398c0 .98-.795 1.776-1.776 1.776h0a1.77 1.77 0 0 1-1.256-.52");
}

.stl9v1b0f {
  width: 4.706px;
  height: 7.104px;
  x: 9.5px;
  y: 19.449px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.353px;
  ry: 2.353px;
}

.t8p5qeflf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.218 21.847v4.706m5.049-.896a1.78 1.78 0 0 1-1.543.896h0c-.98 0-1.776-.795-1.776-1.776v-1.154c0-.981.795-1.776 1.776-1.776h0c.98 0 1.776.795 1.776 1.776v.577h-3.552");
}

</style>
