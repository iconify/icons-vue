<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j98an1bqd"/><path class="ned8kdabr"/><circle class="gol5npbhs"/><path class="vaflsbc5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:picnic" /></template>
<style>
.gol5npbhs {
  cx: 24px;
  cy: 24.005px;
  r: 0.75px;
  fill: currentColor;
}

.j98an1bqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.ned8kdabr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.635 22.35V10.5h3.88c2.192 0 3.97 1.782 3.97 3.98s-1.778 3.98-3.97 3.98h-3.88m0 19.04V25.651l7.85 11.849V25.651");
}

.vaflsbc5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 27.446V37.5m0-27v10.054m12.365-2.178v.048a3.925 3.925 0 1 1-7.85 0v-3.999a3.925 3.925 0 0 1 7.85 0v.049m0 19.052v.049a3.925 3.925 0 1 1-7.85 0v-4a3.925 3.925 0 0 1 7.85 0v.05");
}

</style>
