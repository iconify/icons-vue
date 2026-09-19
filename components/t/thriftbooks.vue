<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="mkbm7zb4h"/><g class="y9tr6bcfx"><rect transform="rotate(-10 35.083 28.517)" class="iux6grbjn"/><path class="snr1c8bvb"/></g><path class="en2sw2bkg"/><rect transform="rotate(-79.865 13.47 26.545)" class="ak6lfhcei"/><path class="m093phbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thriftbooks" /></template>
<style>
.ak6lfhcei {
  width: 31.385px;
  height: 7.056px;
  x: -2.222px;
  y: 23.017px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.302px;
  ry: 1.302px;
}

.en2sw2bkg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.796 38.027h8.759m-8.759-2.536h8.759m-8.758-2.309h8.758");
}

.iux6grbjn {
  width: 6.569px;
  height: 27.553px;
  x: 31.798px;
  y: 14.741px;
  rx: 0.976px;
  ry: 0.976px;
}

.m093phbpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.636 17.055l6.467 1.154");
}

.mkbm7zb4h {
  width: 8.759px;
  height: 36.737px;
  x: 19.796px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.302px;
  ry: 1.302px;
}

.snr1c8bvb {
  d: path("m30.324 19.582l2.143-.378");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
