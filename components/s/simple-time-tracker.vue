<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xg12d3xqf"/><circle class="lz6p-8bid"/><circle class="kykleibpb"/><path class="gxubs-btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simple-time-tracker" /></template>
<style>
.gxubs-btt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.623 15.488l2.529-2.85l-8.339-7.04l-2.454 2.914Zm-31.246 0l-2.529-2.85l8.338-7.04l2.455 2.914Z");
}

.kykleibpb {
  cx: 24.183px;
  cy: 26.144px;
  r: 12.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lz6p-8bid {
  cx: 24.056px;
  cy: 26.186px;
  r: 16.216px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xg12d3xqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.724 21.716l-9.26 9.26l-4.368-4.367");
}

</style>
