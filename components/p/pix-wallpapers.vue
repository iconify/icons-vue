<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m4pp6-wmq"/><path class="d4m807lzb"/><circle class="p_ofpybvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pix-wallpapers" /></template>
<style>
.d4m807lzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.223 30.024L15.53 25.36c-.723-1.25-2.529-1.25-3.251 0L5.754 36.663c-.722 1.251.18 2.815 1.626 2.815h9.617M6.19 18.996h6.023m25.05-1.222H42.5");
}

.m4pp6-wmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.001 16.552l-11.12 19.26c-.94 1.63.235 3.666 2.116 3.666h22.24c1.882 0 3.058-2.036 2.117-3.666l-11.12-19.26c-.94-1.63-3.292-1.63-4.233 0");
}

.p_ofpybvk {
  cx: 16.49px;
  cy: 12.057px;
  r: 3.535px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
