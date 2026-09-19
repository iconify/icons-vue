<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fag2x9bns"/><path class="cot47-bif"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:profita" /></template>
<style>
.cot47-bif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.3 6.733C15.953 7.117 10.11 23.21 6.7 41.267");
}

.fag2x9bns {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.2 11.11h3.296m0-2.427v4.873M13.2 8.683v4.873M8.776 8.682v4.873h2.489M23.396 24.47a7.507 7.507 0 1 0 15.014.001a7.507 7.507 0 0 0-15.015 0v13.71");
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
