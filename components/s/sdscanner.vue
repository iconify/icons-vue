<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jp3xjub3k"/><path class="waozs-a8u"/><path class="nduxb8kzx"/><path class="cnajofbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sdscanner" /></template>
<style>
.cnajofbbq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.7 17.4v15.5h13.8V17.4Zm2.76 2.6v10.3M29.22 20v10.3M31.98 20v10.3M34.74 20v10.3m-10.3-19.19A7.18 7.18 0 0 1 28.36 14m-7.21 9.65a7.18 7.18 0 0 1-3.92-2.93");
}

.jp3xjub3k {
  cx: 22.8px;
  cy: 17.4px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nduxb8kzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39 12.9H21.37a1.13 1.13 0 0 0-1.07 1.19v19.68A1.13 1.13 0 0 0 21.37 35H39a1.13 1.13 0 0 0 1-1.23V14.09a1.13 1.13 0 0 0-1-1.19");
}

.waozs-a8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.4 24.7L7.2 42.4M37.7 4.8H18v32.7h24.5V9.6Z");
}

</style>
