<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="ifv4hdcyk"/><path class="aqa42e3nn"/><path class="m4-9lji-h"/><path class="wyoezgbmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:netmonster" /></template>
<style>
.aqa42e3nn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.186 34.085A15.677 15.677 0 0 1 19.526 4.5m9.435.152a15.678 15.678 0 0 1 1.286 29.251");
}

.ifv4hdcyk {
  cx: 24.273px;
  cy: 19.535px;
  r: 2.376px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m4-9lji-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.597 29.266a9.502 9.502 0 0 1 1.418-18.134m4.481.098a9.502 9.502 0 0 1 1.375 17.883");
}

.wyoezgbmj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.273 21.91L14.77 40.916a18.76 18.76 0 0 0 19.004 0Z");
}

</style>
