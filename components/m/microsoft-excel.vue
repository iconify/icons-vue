<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ym77_n77p"/><path class="gd18z_48w"/><path class="rn0h94bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-excel" /></template>
<style>
.gd18z_48w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16v16a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V16a2 2 0 0 0-2-2h-16a2 2 0 0 0-2 2");
}

.rn0h94bzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.23 14V8.5a4 4 0 0 1 4-4H38.5a4 4 0 0 1 4 4v31a4 4 0 0 1-4 4H17.23a4 4 0 0 1-4-4V34");
}

.ym77_n77p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.82 18.5L15.5 24l-3.68 5.5m7.36-11L15.5 24l3.68 5.5");
}

</style>
