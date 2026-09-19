<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><rect class="pad65gz5v"/><rect class="dhr1x_l3l"/><circle class="e6id5cbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:utm" /></template>
<style>
.dhr1x_l3l {
  width: 15.857px;
  height: 15.857px;
  x: 16.071px;
  y: 16.071px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.095px;
  ry: 3.095px;
}

.e6id5cbkd {
  cx: 24px;
  cy: 24px;
  r: 2.643px;
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

.pad65gz5v {
  width: 26.429px;
  height: 26.429px;
  x: 10.786px;
  y: 10.786px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.548px;
  ry: 3.548px;
}

</style>
