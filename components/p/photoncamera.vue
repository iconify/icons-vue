<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="qfwnw6bjl"/><circle class="m44zgjb-n"/><path class="aq1x1zbsk"/><circle class="th_0luqjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photoncamera" /></template>
<style>
.aq1x1zbsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.112 16.602h8.564m23.012 0h8.109");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m44zgjb-n {
  cx: 24.164px;
  cy: 23.925px;
  r: 9.512px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.qfwnw6bjl {
  cx: 24.101px;
  cy: 24.022px;
  r: 13.428px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.th_0luqjs {
  cx: 36.73px;
  cy: 11.242px;
  r: 1.871px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
