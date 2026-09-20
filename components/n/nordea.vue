<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="meufweb1n"/><rect class="f12g2-7my"/><path class="qt2c_ibbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nordea" /></template>
<style>
.f12g2-7my {
  width: 3.908px;
  height: 5.178px;
  x: 15.576px;
  y: 22.73px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.954px;
  ry: 1.954px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.meufweb1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 27.908v-7.816l5.178 7.816v-7.816");
}

.qt2c_ibbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.24 24.684c0-1.08.875-1.954 1.954-1.954m-1.954 0v5.178m18.26-1.954a1.954 1.954 0 0 1-3.908 0v-1.27a1.954 1.954 0 0 1 3.908 0m0 3.224v-3.224m-5.942 2.238a1.954 1.954 0 0 1-3.652-.968v-1.27a1.954 1.954 0 0 1 3.908 0v.635h-3.909m-1.71-.635a1.954 1.954 0 0 0-3.908 0v1.27a1.954 1.954 0 0 0 3.908 0m0 1.954v-7.816");
}

</style>
