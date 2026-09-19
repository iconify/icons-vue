<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="d4wwv8b7p"/><path class="lnmp9wbpb"/><circle class="ttw971u4d"/><path class="u18kjx_zj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panasonic-tsunagetenet-access-point" /></template>
<style>
.d4wwv8b7p {
  width: 15px;
  height: 15px;
  x: 10.75px;
  y: 22.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.5px;
  ry: 1.5px;
}

.lnmp9wbpb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31 22.5v18c0 1.108-.892 2-2 2H7.5c-1.108 0-2-.892-2-2V19c0-1.108.892-2 2-2h18M31 5.5c6.351 0 11.5 5.149 11.5 11.5M31 10.5a6.5 6.5 0 0 1 6.5 6.5");
}

.ttw971u4d {
  cx: 31px;
  cy: 17px;
  r: 0.75px;
  fill: currentColor;
}

.u18kjx_zj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.75 29.75h15");
}

</style>
