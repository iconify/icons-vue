<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u99-xdb-w"/><ellipse class="oeoq6s2ux"/><path class="xhatkd-ng"/><ellipse class="zkl9o1bvy"/><ellipse class="sv4moy8cp"/><path class="r8qzh0bae"/><circle class="ypb8nbbxu"/><circle class="cj7jd1shj"/><path class="fox03tx9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tanglemaster3d" /></template>
<style>
.cj7jd1shj {
  cx: 15.37px;
  cy: 8.05px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fox03tx9s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.37 10.05c0 5.51 4.47 7.81 6.42 9.15s15.87 7.2 15.87 17.48");
}

.oeoq6s2ux {
  cx: 10.34px;
  cy: 36.68px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.43px;
  ry: 2.85px;
}

.r8qzh0bae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.23 36.68v2.42c0 1.58 2 2.85 4.43 2.85s4.43-1.27 4.43-2.85v-2.42m-31.75 0C10.34 31.59 24 24.41 24 19.2s-5.44-4.2-5.23 0C19 24 33.22 25 33.23 10.05");
}

.sv4moy8cp {
  cx: 37.66px;
  cy: 36.68px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.43px;
  ry: 2.85px;
}

.u99-xdb-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.23 8.05h7.27m-25.13 0h13.86m-25.73 0h7.87M5.5 9.55v-3m37 3v-3");
}

.xhatkd-ng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.91 36.68v2.42c0 1.58 2 2.85 4.43 2.85s4.43-1.27 4.43-2.85v-2.42");
}

.ypb8nbbxu {
  cx: 33.23px;
  cy: 8.05px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zkl9o1bvy {
  cx: 24px;
  cy: 39.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.43px;
  ry: 2.85px;
}

</style>
