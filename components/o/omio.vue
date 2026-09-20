<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="xx15o1b0u"/><circle class="oi67-nurx"/><path class="dtto7mbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:omio" /></template>
<style>
.dtto7mbfv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.368 42.494a19 19 0 0 1-.155-2.418c0-10.494 8.507-19 19-19a19 19 0 0 1 7.285 1.452m-14.906 19.98a8 8 0 0 1 7.621-10.432a8 8 0 0 1 7.29 4.703");
}

.oi67-nurx {
  cx: 15.498px;
  cy: 15.492px;
  r: 6px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xx15o1b0u {
  width: 37px;
  height: 37px;
  x: 5.498px;
  y: 5.492px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
