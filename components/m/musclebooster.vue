<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect transform="rotate(45 10.107 37.893)" class="jl6we-bcu"/><rect transform="rotate(45 24.2 23.8)" class="a06guibyu"/><rect transform="rotate(45 17.137 30.863)" class="roxty2b_w"/><rect transform="rotate(45 35.023 12.976)" class="ohzze0zkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:musclebooster" /></template>
<style>
.a06guibyu {
  width: 44.458px;
  height: 6.132px;
  x: 1.97px;
  y: 20.735px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.jl6we-bcu {
  width: 6.132px;
  height: 6.132px;
  x: 7.041px;
  y: 34.827px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.ohzze0zkf {
  width: 6.132px;
  height: 15.015px;
  x: 31.957px;
  y: 5.469px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

.roxty2b_w {
  width: 26.783px;
  height: 6.132px;
  x: 3.746px;
  y: 27.797px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

</style>
