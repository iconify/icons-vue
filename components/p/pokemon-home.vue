<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o9nc2qu1s"/><path class="ea_8fiigr"/><circle class="klvt3wbhq"/><path class="i9clfwm2k"/><circle class="uuoxaqi_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pokemon-home" /></template>
<style>
.ea_8fiigr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.561 37.68a24.75 24.75 0 0 1 12.855-7.357M42.5 37.68a24.75 24.75 0 0 0-12.854-7.357");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.klvt3wbhq {
  cx: 24px;
  cy: 29.366px;
  r: 5.237px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o9nc2qu1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 35.671V35.5C5.5 25.282 13.783 17 24 17s18.5 8.282 18.5 18.5v.171");
}

.uuoxaqi_y {
  cx: 24px;
  cy: 29.366px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
