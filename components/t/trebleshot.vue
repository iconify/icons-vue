<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mmvbtks0y"/><circle class="n1o5xdbyf"/><circle class="a0inrckln"/><circle class="jg5qt0bwv"/><path class="o8e9ukbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trebleshot" /></template>
<style>
.a0inrckln {
  cx: 11.07px;
  cy: 13.25px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jg5qt0bwv {
  cx: 36.93px;
  cy: 13.25px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mmvbtks0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.12 19.53v1.18a14.93 14.93 0 0 0 11.01 14.42M32.47 8.42a14.93 14.93 0 0 0-19 1.74M30.41 34.2a14.93 14.93 0 0 0 8-17.35");
}

.n1o5xdbyf {
  cx: 24px;
  cy: 35.64px;
  r: 3.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o8e9ukbny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.54 39.31a6.58 6.58 0 0 0 7.84 2.46a6.3 6.3 0 0 0 1.28-.68a6.57 6.57 0 0 0-7.33-10.91m22.42-13.89A6.57 6.57 0 0 0 31.91 9a6.7 6.7 0 0 0-.81 1.21a6.57 6.57 0 0 0 2.79 8.87M10.65 6.69a6.57 6.57 0 0 0-6.07 5.53a7 7 0 0 0-.07 1.45a6.57 6.57 0 1 0 13.12-.84");
}

</style>
