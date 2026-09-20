<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="m603q32ow"/><path class="ddr_4jb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-pay" /></template>
<style>
.ddr_4jb3l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.5 20.054v4.936a2.991 2.991 0 1 1-5.982 0v-4.936m-2.992 4.936a2.991 2.991 0 1 1-5.982 0v-1.945a2.991 2.991 0 1 1 5.982 0m0 4.936v-7.927");
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

.m603q32ow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 27.946V15.98h3.917c2.215 0 4.01 1.799 4.01 4.018s-1.795 4.018-4.01 4.018H11.5m25 .974v4.038a2.99 2.99 0 0 1-2.991 2.991a2.98 2.98 0 0 1-2.115-.876");
}

</style>
