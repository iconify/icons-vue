<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hhzl52b8p"/><path class="f4uyk9bvm"/><circle class="cxl1mqi6x"/><circle class="kr-urympt"/><path class="t96266b6z"/><circle class="ghcpm2b3d"/><circle class="m9t02k2ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mbestyle" /></template>
<style>
.cxl1mqi6x {
  cx: 17.521px;
  cy: 15.776px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f4uyk9bvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.476 37.556h3.32a3 3 0 0 0 3-3V13.285c0-4.418-3.37-8-12-8h-3.32");
}

.ghcpm2b3d {
  cx: 13.927px;
  cy: 22.042px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hhzl52b8p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.658 37.556h7.365v3.262A3.68 3.68 0 0 1 22.34 44.5h0a3.68 3.68 0 0 1-3.682-3.682zm6.818-32.271h-6.271c-8.501 0-12 3.582-12 8v21.271a3 3 0 0 0 3 3h24.27a3 3 0 0 0 3-3V13.285c0-4.418-3.368-8-12-8");
}

.kr-urympt {
  cx: 27.16px;
  cy: 15.776px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m9t02k2ha {
  cx: 30.66px;
  cy: 22.042px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t96266b6z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.157 19.307a2.933 2.933 0 0 1-5.633 0");
}

</style>
