<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="x3oj8zuek"/><path class="avswbvzyi"/><circle class="jjjmw9j_i"/><circle class="agidb-rsk"/><circle class="vb6scem3v"/><path class="yc7fbactm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panasonic-smart-laundry" /></template>
<style>
.agidb-rsk {
  cx: 13.75px;
  cy: 37.5px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.avswbvzyi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.5 13.5A1.5 1.5 0 0 1 32 12");
}

.jjjmw9j_i {
  cx: 37.25px;
  cy: 17.75px;
  r: 2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.vb6scem3v {
  cx: 10.5px;
  cy: 31.75px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.x3oj8zuek {
  cx: 33.5px;
  cy: 12px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yc7fbactm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.501 28.959C6.493 28.674 7.904 27.046 10 27c2.267-.049 4.573 2 7 2s4.573-2 7-2s4.573 2 7 2s4.733-2.049 7-2c2.096.046 3.507 1.674 5.499 1.959m-13.181-6.678l.647 6.717m-13.93-.001l.647-6.717m13.475 8.711l.332 3.449a27.03 27.03 0 0 1-14.98 0l.333-3.449m.652-6.785l-3.78-4.215l4.5-4.597a9 9 0 0 0 11.57 0l4.5 4.597l-3.78 4.215");
}

</style>
