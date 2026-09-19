<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="e1j_-ixjq"/><circle class="a3l4hac-f"/><path class="cyzghmgps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbab-bank" /></template>
<style>
.a3l4hac-f {
  cx: 38.637px;
  cy: 28px;
  r: 0.75px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

.cyzghmgps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.187 20l-1.1 5.95");
}

.e1j_-ixjq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.972 27.124c.49.639 1.106.877 1.961.877h1.185a1.996 1.996 0 0 0 1.995-1.996v-.009A1.996 1.996 0 0 0 12.118 24H10.81a2 2 0 0 1-1.998-1.997c0-1.106.897-2.003 2.003-2.003h1.177c.856 0 1.471.238 1.962.877M34.143 24a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.296m-11.39 0a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.296m11.761 1.35h-3.544M23.5 28l2.65-8l2.65 8");
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
