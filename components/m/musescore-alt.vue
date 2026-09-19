<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><circle class="txm9nljof"/><path class="gfm18cbnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:musescore-alt" /></template>
<style>
.gfm18cbnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.5 25.35v7.2m0-7.2a4.513 4.513 0 0 1 4.5-4.5h0a4.513 4.513 0 0 1 4.5 4.5m0 0v2.925a4.513 4.513 0 0 0 4.5 4.5h.001a4.51 4.51 0 0 0 4.499-4.5V23.1m-18 2.25a4.513 4.513 0 0 0-4.5-4.5h0a4.513 4.513 0 0 0-4.5 4.5v7.2m18-12.825a4.513 4.513 0 0 1 4.5-4.5h.001a4.51 4.51 0 0 1 4.5 4.5");
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

.txm9nljof {
  cx: 33px;
  cy: 20.4px;
  r: 0.75px;
  fill: currentColor;
}

</style>
