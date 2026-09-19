<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="l1tzfmbxu"/><circle class="uu_zs53vq"/><path class="ekwl27b8s"/><circle class="xlugxbb9v"/></g><circle class="sacx76b6x"/><path class="ldp87n3-i"/><path class="oyd42oblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:offline-games" /></template>
<style>
.ekwl27b8s {
  d: path("m15.4 36.776l8.112-30.111a2.924 2.924 0 0 1 3.582-2.063l11.288 3.041a2.923 2.923 0 0 1 2.061 3.581l-8.11 30.11a2.925 2.925 0 0 1-3.584 2.064l-11.287-3.04a2.923 2.923 0 0 1-2.061-3.582M26.998 16.34l-3.332 12.38m8.994-11.057L29.315 30.09m-8.399-5.544l12.329 3.321M22.76 18.631l12.094 3.258m-7.678-.352l1.854 3.428m.7-2.79l-3.263 1.998m4.553 4.458l1.96 3.406m.735-2.73l-3.357 1.973");
}

.l1tzfmbxu {
  cx: 22.331px;
  cy: 21.684px;
  r: 1.169px;
}

.ldp87n3-i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.724 16.746c1.34-1.463 4.092-1.805 5.41 0m-6.726-1.95c2.225-2.442 6.498-2.637 8.43 0");
}

.oyd42oblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.459 13.09c2.778-3.49 8.912-3.427 12.329 0M9.652 8.459l6.968 12.068");
}

.sacx76b6x {
  cx: 13.72px;
  cy: 18.87px;
  r: 1.169px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uu_zs53vq {
  cx: 29.694px;
  cy: 17.622px;
  r: 1.169px;
}

.xlugxbb9v {
  cx: 23.883px;
  cy: 16.056px;
  r: 1.169px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
