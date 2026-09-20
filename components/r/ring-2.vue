<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="s_q-kvbwl"/><rect transform="matrix(-1 0 0 -1 64.963 46.384)" class="xcc7c4b3d"/><path class="fe97wd1lp"/><circle class="hlv9jkmva"/><path class="fo99r-b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ring-2" /></template>
<style>
.fe97wd1lp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 21.574c0-.972.394-1.851 1.03-2.488s1.517-1.03 2.488-1.03M12 21.574v6.755");
}

.fo99r-b1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.525 18.055v10.274m9.253 0v-6.755a3.518 3.518 0 0 0-7.037 0v6.755");
}

.hlv9jkmva {
  cx: 17.525px;
  cy: 15.645px;
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

.s_q-kvbwl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36 21.574v7.986a3.52 3.52 0 0 1-3.518 3.519a3.5 3.5 0 0 1-2.488-1.03");
}

.xcc7c4b3d {
  width: 7.037px;
  height: 10.274px;
  x: 28.963px;
  y: 18.055px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.518px;
  ry: 3.518px;
}

</style>
