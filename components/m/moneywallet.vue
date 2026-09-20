<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="qn3rf_bux"/><circle class="dak2lnb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:moneywallet" /></template>
<style>
.dak2lnb8m {
  cx: 36.47px;
  cy: 24px;
  r: 0.8px;
  fill: currentColor;
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.qn3rf_bux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.34 16.8a3.6 3.6 0 0 0 0 7.2h1.22m0 0h1.22a3.59 3.59 0 0 1 3.59 3.59v.01a3.59 3.59 0 0 1-3.58 3.6h-.01M24 18c-1-.83-2.06-1.21-4.47-1.21h-1.19M15.09 30c1 .83 2.07 1.21 4.47 1.21h1.22M19.56 33V15m16.79 5.4h7.15v7.2h-7.15a2.85 2.85 0 0 1-2.85-2.85v-1.5a2.85 2.85 0 0 1 2.85-2.85");
}

</style>
