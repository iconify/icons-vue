<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="sz673_bsj"/><circle class="ofg1wbcsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:natural-cycles" /></template>
<style>
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

.ofg1wbcsd {
  cx: 35.524px;
  cy: 17.842px;
  r: 3.341px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.sz673_bsj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.574 29.5V17.842L20.298 29.5V17.842M30.62 25.59v.048a3.86 3.86 0 0 1-3.863 3.862h0a3.86 3.86 0 0 1-3.862-3.862v-3.934a3.86 3.86 0 0 1 3.862-3.862h0a3.86 3.86 0 0 1 3.862 3.862v.047");
}

</style>
