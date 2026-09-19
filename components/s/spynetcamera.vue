<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="dxf53r5_i"/><circle class="zqw3jbbqw"/><path class="eewz5q62v"/><path class="hcddpdnxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spynetcamera" /></template>
<style>
.dxf53r5_i {
  cx: 24px;
  cy: 24px;
  r: 7.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.eewz5q62v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.3 5.5h29.4c2.1 0 3.8 1.7 3.8 3.8v29.4c0 2.1-1.7 3.8-3.8 3.8H9.3c-2.1 0-3.8-1.7-3.8-3.8V9.3c0-2.1 1.7-3.8 3.8-3.8m33.2 14.8h-7.7m-21.7.1H5.5");
}

.hcddpdnxq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.6 14.7v-4c0-1 .8-1.8 1.8-1.8h4.9c1 0 1.8.8 1.8 1.8v4.8c0 1-.8 1.8-1.8 1.8h-4.2");
}

.zqw3jbbqw {
  cx: 24px;
  cy: 24px;
  r: 11.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
