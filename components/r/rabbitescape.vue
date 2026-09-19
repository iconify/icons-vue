<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d3j1umbbb"/><path class="i3m_gcb5p"/><ellipse class="ffyfk3buk"/><path class="nl_rhkbay"/><path class="q0fs8252t"/><circle class="i9ucq7mme"/><path class="zgorrubgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rabbitescape" /></template>
<style>
.d3j1umbbb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.85 35.94c2.5-1.08 4.73-3.95 5.88-6.32h0C27.41 26.16 28 20 25.2 18.16m-5.01.32a14.1 14.1 0 0 0-4.84 5.41c-1.54 3-2.48 8.66-.34 11.21");
}

.ffyfk3buk {
  cx: 16.48px;
  cy: 37.45px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.24px;
  ry: 2.51px;
}

.i3m_gcb5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.4 10.58a3 3 0 0 0-1.31 1.16c-1.11 1.87.2 5 2.1 6h0c1.9 1.08 5.54.52 6.58-1.35s-.24-4.7-2.09-5.78a5.47 5.47 0 0 0-2.84-.61");
}

.i9ucq7mme {
  cx: 27.78px;
  cy: 13.79px;
  r: 0.82px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nl_rhkbay {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.69 37.75c1.88.09 3.27.67 3.27 1.34h0c0 .75-1.7 1.36-3.79 1.36a8.1 8.1 0 0 1-3-.52m1.92-26.28c-.75.69.37 3.74 1.3 5.15s2.94 3.32 3.63 2.75s0-3-.85-4.48s-3.32-4.07-4.08-3.42m3.75-9.11c1.13-.37 2.22 2 2.6 3.34s.78 3.53-.27 3.92s-2.28-1.8-2.71-3.18s-.76-3.71.38-4.08");
}

.q0fs8252t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.19 5.24a1 1 0 0 1 .62-.67h0C26 4.2 27 6.58 27.42 7.91a9 9 0 0 1 .41 2.36");
}

.zgorrubgw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.41 23.77l-2.95 4.37l-2.83-1.86l6.71-11l3.36 2.22m4.1 26l-2-2l14.65-14.35l1.92 1.93Z");
}

</style>
