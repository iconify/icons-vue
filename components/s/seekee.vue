<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="d1mdodj5e"/><circle class="jp5ga5bmw"/><circle class="rab4qyhgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:seekee" /></template>
<style>
.d1mdodj5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.555 23.658a8.02 8.02 0 0 1-5.432 7.918a8 8 0 0 1-8.826-12.563a8.02 8.02 0 0 1 9.293-2.424a8.02 8.02 0 0 1 5.435-7.918a8 8 0 0 1 8.823 12.566a8.02 8.02 0 0 1-9.293 2.42");
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

.jp5ga5bmw {
  cx: 32.895px;
  cy: 14.303px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rab4qyhgh {
  cx: 22.764px;
  cy: 22.115px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
