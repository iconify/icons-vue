<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="q44yu1imo"/><path class="n9dwkjv-s"/><path class="j222ml7jw"/><path class="jlclsab8e"/><circle class="xyws_3b5x"/><circle class="q55dmvbkp"/><path class="t8qe0v70q"/><path class="i_356xw5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:orbia" /></template>
<style>
.i_356xw5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.23 9.88a8.4 8.4 0 0 1 .51 4.44s-4.12-.42-5.83-2.5");
}

.j222ml7jw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 14.77c-4.1 2.94-3.85 13.12.28 16.37");
}

.jlclsab8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.3 29.43c.44 5.64 7.18 9.34 16.7 9.34c16.43 0 17.83-12.56 17.83-17.41c0-3-1.52-5.92-4-7");
}

.n9dwkjv-s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14 11.35c-4.36.39-6.63 3.88-6.28 7.76");
}

.q44yu1imo {
  cx: 24px;
  cy: 24.09px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.q55dmvbkp {
  cx: 30.33px;
  cy: 23.96px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t8qe0v70q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.67 11.22c5.23.71 8 4.08 8.65 9M15.46 10.13c-1.1.68-2.09 2.76-2.28 4.4c0 0 3 1 7.49-2.82m6.14-.97c-1.3 2.06-4.71 3.68-6.71 4.19a5.7 5.7 0 0 1-.1-2.64");
}

.xyws_3b5x {
  cx: 17.67px;
  cy: 23.96px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
