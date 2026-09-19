<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q_snuccof"/><circle class="avu30ybzo"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:prixtel" /></template>
<style>
.avu30ybzo {
  cx: 28.847px;
  cy: 25.837px;
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

.q_snuccof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.403 22.775a3.5 3.5 0 0 0 3.5 3.5h0a3.5 3.5 0 0 0 3.5-3.5V20.5a3.5 3.5 0 0 0-3.5-3.5h0a3.5 3.5 0 0 0-3.5 3.5m0-3.5v14");
}

</style>
