<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="mq3m4zjzx"/><path class="yp4_56bgt"/><circle class="n6-wxuajq"/><circle class="gmo-58b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shizuku" /></template>
<style>
.gmo-58b6t {
  cx: 21.63px;
  cy: 28.91px;
  r: 1.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.mq3m4zjzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.31 33.96h1.44L35.5 24l-5.75-9.96h-11.5l-2.81 4.87");
}

.n6-wxuajq {
  cx: 12.35px;
  cy: 25.53px;
  r: 1.1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yp4_56bgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.65 42.5l1.92-5.28a13.3 13.3 0 0 0 .16-8.63l.34-.62a12.13 12.13 0 0 0 1.14-6.35a12 12 0 0 0-5.92.3l-.21.07a13.5 13.5 0 0 0-3.49-1.9h0a13.5 13.5 0 0 0-3.91-.79l-.11-.19a12.1 12.1 0 0 0-4.34-4A12 12 0 0 0 8 20.67q-.09.34-.15.69a13.7 13.7 0 0 0-2.35 1.92");
}

</style>
