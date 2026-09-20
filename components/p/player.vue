<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h8ikdhmsq"/><path class="vqf-2jd4j"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:player" /></template>
<style>
.h8ikdhmsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.302 24.648v2.694a1.995 1.995 0 0 1-1.995 1.995c-.551 0-1.05-.223-1.41-.584");
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

.vqf-2jd4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.302 21.356v3.292a1.995 1.995 0 0 1-3.99 0v-3.292m12.193 1.996c0-1.102.893-1.996 1.995-1.996m-1.995 0v5.288m-20.981-7.981v6.983c0 .551.447.998.998.998h.299m5.379-1.996a1.995 1.995 0 0 1-3.99 0v-1.297a1.995 1.995 0 0 1 3.99 0m0 3.293v-5.288m11.953 4.281a1.995 1.995 0 0 1-3.729-.988v-1.297a1.995 1.995 0 1 1 3.99 0V24h-3.99M9.5 24.648a1.995 1.995 0 1 0 3.99 0v-1.297a1.995 1.995 0 0 0-3.99 0m0-1.995v7.981");
}

</style>
