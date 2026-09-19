<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="wlb72g3hu"/><path class="zbysfv5my"/><path class="zxfrf2inp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myradar" /></template>
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

.wlb72g3hu {
  cx: 33.243px;
  cy: 24.861px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zbysfv5my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.695 24.191c0 3.59-5.532 16.644-6.5 16.65c-1.166.008-6.5-13.06-6.5-16.65a6.5 6.5 0 1 1 13 0");
}

.zxfrf2inp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.036 5.5c-1.961 5.317 1.515 9.074 1.151 14.528M15.65 5.5s-5.576 4.723-4.399 7.313c2.158 4.746-5.741 7.227-5.751 7.203M22.725 5.5s-2.75 5.618-1.944 8.365C23.942 24.63 5.5 27.57 5.5 27.57M30.47 5.5c-2.321 6.472.283 9.343.062 12.76m-3.734 7c.135.34-4.155 3.442-6.782 3.202c-4.964-.454-13.4 6.714-14.516 6.151m2.55 7.607c9.5-11.02 13.58-6.86 20.67-10.28");
}

</style>
