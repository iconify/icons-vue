<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="y_z2nob1n"/><path class="s-u_cgmle"/><path class="qrtigw-ng"/><path class="i16p0c1dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rfid-tools" /></template>
<style>
.i16p0c1dh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.755 26.764a2.35 2.35 0 0 0-2.474-2.35a2.44 2.44 0 0 0-2.222 2.483v2.18a2.35 2.35 0 0 0 2.348 2.353h0a2.35 2.35 0 0 0 2.348-2.353h-2.348M8.11 31.43v-7.02h2.298a2.358 2.358 0 0 1 0 4.715H8.11m2.298.001l2.298 2.303m2.884.001v-7.02h2.298a2.358 2.358 0 0 1 0 4.715h-2.299m2.299.001l2.298 2.303");
}

.qrtigw-ng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.975 21.74A13.92 13.92 0 0 0 28.054 7.82m-10.6 6.872H8.01a3.51 3.51 0 0 0-3.51 3.51V36.67a3.51 3.51 0 0 0 3.51 3.51h31.98a3.51 3.51 0 0 0 3.51-3.51v-9.58");
}

.s-u_cgmle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.058 21.74a9.004 9.004 0 0 0-9.004-9.004");
}

.y_z2nob1n {
  cx: 29.736px;
  cy: 20.058px;
  r: 2.528px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
