<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pyc8uabac"/><ellipse class="cpq22kdcu"/><path class="hq6gxebqt"/><ellipse class="vk9cs3b9i"/><path class="yijqtcb1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:owly" /></template>
<style>
.cpq22kdcu {
  cx: 13.921px;
  cy: 24.725px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.338px;
  ry: 4.348px;
}

.hq6gxebqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.935 32.722A9.438 9.438 0 0 1 6.337 19.12M24 39.792l-5.065-7.07M24 13.592l18.925-5.384l-1.262 10.912");
}

.pyc8uabac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 13.592L5.075 8.208L6.337 19.12");
}

.vk9cs3b9i {
  cx: 34.079px;
  cy: 24.725px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.338px;
  ry: 4.348px;
}

.yijqtcb1c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.065 32.722A9.438 9.438 0 0 0 41.663 19.12M24 39.792l5.065-7.07");
}

</style>
