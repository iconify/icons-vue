<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bfgbvhbhs"/><rect class="a37bw_bbi"/><rect transform="rotate(45)" class="mjuktmcrf"/><circle class="z97s58bjx"/><path class="xe08-obik"/><circle class="mlx2hs5wa"/><circle class="vh2cwzokd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:times-car" /></template>
<style>
.a37bw_bbi {
  width: 17px;
  height: 5.5px;
  x: 11.5px;
  y: 19px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

.bfgbvhbhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.5 19v-3.75c0-1.108.892-2 2-2h7c1.108 0 2 .892 2 2V19");
}

.mjuktmcrf {
  width: 13.5px;
  height: 5px;
  x: 45.571px;
  y: -2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.5px;
  ry: 2.5px;
}

.mlx2hs5wa {
  cx: 14.5px;
  cy: 21.75px;
  r: 0.75px;
  fill: currentColor;
}

.vh2cwzokd {
  cx: 25.5px;
  cy: 21.75px;
  r: 0.75px;
  fill: currentColor;
}

.xe08-obik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 19a1.75 1.75 0 1 1 3.5 0m10.753 11.253l1.97 1.97M25.5 24.5v2.25m-11-2.25v2.25");
}

.z97s58bjx {
  cx: 20px;
  cy: 20px;
  r: 14.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
