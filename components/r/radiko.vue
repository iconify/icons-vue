<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="d_cugy3hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:radiko" /></template>
<style>
.d_cugy3hx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.145 24.284a4.638 4.638 0 0 1-.1 7.322m3.605-9.82a8.856 8.856 0 0 1-.124 12.366m3.706-14.916a13.22 13.22 0 0 1 3.238 8.67h0c0 3.267-1.209 6.418-3.394 8.846M15.09 11.248v24.79m0-15.609c0-5.05 4.131-9.181 9.18-9.181h0");
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

</style>
