<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="org46pyoj"/><path class="z7j0y4_rx"/><ellipse class="f0-n15l7s"/><ellipse class="acpgh0n8g"/><ellipse class="iniu2n5qq"/><path class="bi8hjzr8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spacepeng" /></template>
<style>
.acpgh0n8g {
  cx: 23.83px;
  cy: 22.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.34px;
  ry: 7.37px;
}

.bi8hjzr8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.75 35.35c2.43 1.6 6.66 1.55 8.44 0c-1.29 3.73-6.91 3.75-8.44 0");
}

.f0-n15l7s {
  cx: 23.92px;
  cy: 22.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.6px;
  ry: 2.61px;
}

.iniu2n5qq {
  cx: 23.86px;
  cy: 21.85px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 8.25px;
  ry: 9.04px;
}

.org46pyoj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 25.9c0 22.13 39 22.14 39 0c0-9.53-8.67-19.15-19.56-19.15A19.72 19.72 0 0 0 4.5 25.9");
}

.z7j0y4_rx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m35.15 10.47l.92-1.36c1.84.3 3-1.73.73-3.09s-3.51.48-2.4 2.15l-.75 1.32m-20.94.94l-.93-1.36c-1.84.3-3-1.73-.72-3.1s3.51.48 2.39 2.16l.75 1.31");
}

</style>
