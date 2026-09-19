<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="y208g0c4u"/><circle class="g_c6b_3oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pepper-1" /></template>
<style>
.g_c6b_3oa {
  cx: 39.912px;
  cy: 38.106px;
  r: 0.75px;
  fill: currentColor;
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

.y208g0c4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.338 38.316v-5.84h1.912c1.08 0 1.957.877 1.957 1.96s-.876 1.962-1.957 1.962H9.338m9.74 1.918v-5.84h1.912c1.081 0 1.957.877 1.957 1.96s-.876 1.962-1.957 1.962h-1.912m5.325 1.918v-5.84h1.912a1.96 1.96 0 0 1 0 3.922h-1.913m9.731 1.918v-5.84h1.912c1.081 0 1.957.877 1.957 1.96s-.876 1.962-1.957 1.962h-1.912m1.912 0l1.912 1.916m-23.402-2.919h1.904m1.016 2.921h-2.92v-5.841h2.92m12.213 2.92h1.904m1.016 2.921h-2.92v-5.841h2.92");
}

</style>
