<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="fwk17quqr"/><circle class="k60heo9wk"/><path class="bi5bg3bub"/><path class="e-m1xzb6v"/><path class="od7ojtbcd"/><path class="f96jj501t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stadtrad-hamburg" /></template>
<style>
.bi5bg3bub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.616 31.425l-4.89 6.285h-6.41l4.908-6.285z");
}

.e-m1xzb6v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.686 37.715l-2.843-8.621H25.75m-4 .342l1.974 8.276m-3.252-8.276h2.662");
}

.f96jj501t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.682 24.658v-10.8h6.389v10.8m3.329 0v-12.6m7.2.002v12.597M24 8.46V4.5m-1.8 1.8h3.6m5.13 18.358v-10.8h6.388v10.8M20.4 12.06a3.6 3.6 0 1 1 7.2 0m.009.449h1.342m-8.551 0h-1.35m-5.203-.378l-.689-1.61l-1.742.17l1.05-1.401l-1.02-1.424l1.738.208l.723-1.594l.69 1.61l1.742-.17l-1.049 1.4l1.019 1.425l-1.739-.208Zm20.248 0l-.69-1.61l-1.742.17l1.05-1.401l-1.02-1.424l1.739.208l.723-1.594l.689 1.61l1.742-.17l-1.049 1.4l1.019 1.425l-1.738-.208Z");
}

.fwk17quqr {
  cx: 30.686px;
  cy: 37.715px;
  r: 3.6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k60heo9wk {
  cx: 17.314px;
  cy: 37.715px;
  r: 3.6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.od7ojtbcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.682 26.997a59.4 59.4 0 0 1-3.78 16.108q17.103.79 34.196 0a58.3 58.3 0 0 1-3.78-16.108m-28.616 0v-2.34h30.596v2.34Z");
}

</style>
