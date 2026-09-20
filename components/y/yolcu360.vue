<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mliqxybym"/><rect class="kn1l15b6h"/><circle class="jblfsntex"/><path class="n9lxk8brt"/><circle class="j_0z0x3mf"/><path class="xmsyqljlo"/><rect class="l5001qbfk"/><path class="hy3bsge0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yolcu360" /></template>
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

.hy3bsge0l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.64 16.328v4.01a2.43 2.43 0 1 0 4.86 0v-4.01m-14.316-3.281v9.72m7.08-1.224a2.43 2.43 0 0 1-4.54-1.206v-1.58a2.429 2.429 0 0 1 4.537-1.21m-16.901 2.79v5.71");
}

.j_0z0x3mf {
  cx: 37.186px;
  cy: 28.018px;
  r: 1.314px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jblfsntex {
  cx: 25.53px;
  cy: 32.759px;
  r: 2.194px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kn1l15b6h {
  width: 4.387px;
  height: 6.622px;
  x: 29.9px;
  y: 28.33px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.194px;
  ry: 2.194px;
}

.l5001qbfk {
  width: 4.86px;
  height: 6.439px;
  x: 16.785px;
  y: 16.328px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.43px;
  ry: 2.43px;
}

.mliqxybym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 34.394c.457.383.951.559 2.06.559h.258a1.655 1.655 0 0 0 0-3.31M17 28.883c.458-.382.952-.556 2.06-.553l.258.002a1.655 1.655 0 0 1 0 3.31m-1.272 0h1.272");
}

.n9lxk8brt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.53 29.138c-.366-.479-.923-.808-1.846-.808h-.154a2.194 2.194 0 0 0-2.194 2.194v2.235");
}

.xmsyqljlo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.36 16.328v4.01a2.43 2.43 0 1 1-4.86 0v-4.01");
}

</style>
