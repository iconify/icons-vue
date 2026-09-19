<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qz6ig2b2n"/><circle class="ynut_cb6q"/><circle class="nnckv5bog"/><circle class="ymwap4c7i"/><circle class="pc_o8_bnv"/><circle class="y0863hbds"/><path class="muuc4jb8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:star-walk-2" /></template>
<style>
.muuc4jb8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.046 15.39v-4.981m0 8.864v4.98m1.941-6.922h4.981m-8.864 0h-4.981m-4.98 9.708l9.117-7.513m-1.266 14.773l5.064-3.715M11.675 34.13l-2.87-2.617m14.773-16.208l4.221-2.195m6.415-1.097l4.39.844M23.831 25.435l-1.013-3.039");
}

.nnckv5bog {
  cx: 24.675px;
  cy: 28.39px;
  r: 1.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pc_o8_bnv {
  cx: 6.273px;
  cy: 29.065px;
  r: 1.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qz6ig2b2n {
  cx: 31.006px;
  cy: 11.675px;
  r: 1.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.y0863hbds {
  cx: 21.046px;
  cy: 17.331px;
  r: 1.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ymwap4c7i {
  cx: 14.208px;
  cy: 36.325px;
  r: 1.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ynut_cb6q {
  cx: 41.727px;
  cy: 13.533px;
  r: 1.773px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
