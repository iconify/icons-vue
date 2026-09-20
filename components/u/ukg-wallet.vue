<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="hws-dacnc"/><path class="cdvfakbdt"/><rect class="r7y3_fb3j"/><circle class="w7szwlvbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ukg-wallet" /></template>
<style>
.cdvfakbdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.96 16.49v18.18a3.26 3.26 0 0 1-6.52 0V16.49m-12.89 0v18.18a3.26 3.26 0 0 1-6.52 0V16.49");
}

.hws-dacnc {
  width: 25.93px;
  height: 6.51px;
  x: 11.03px;
  y: 31.43px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.99px;
  ry: 2.99px;
}

.r7y3_fb3j {
  width: 39px;
  height: 6.43px;
  x: 4.5px;
  y: 10.06px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.95px;
  ry: 2.95px;
}

.w7szwlvbt {
  cx: 24px;
  cy: 22.47px;
  r: 3.31px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
