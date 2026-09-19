<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axjwb7mbv"/><circle class="l8tvfenxp"/><path class="pmjp26udl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weathercan" /></template>
<style>
.axjwb7mbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.51 15.44a6.94 6.94 0 0 0-12.42 4A6.23 6.23 0 0 0 8.38 31m9.19.8h10.74a4.87 4.87 0 0 0 4.87-4.87a4.8 4.8 0 0 0-.58-2.3");
}

.l8tvfenxp {
  cx: 30.18px;
  cy: 17.11px;
  r: 6.02px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.pmjp26udl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.18 4.5v5.1m8.92-1.41l-3.61 3.61m7.3 5.31H37.7m1.4 8.92l-3.61-3.6M21.26 8.19l3.61 3.61m-8.75 21.51l-1.81-5.53l-4.24 4a3.83 3.83 0 0 0 1.2 6.39l.36.11l.38.08a3.83 3.83 0 0 0 4.11-5.05m5.5 6.11l-1.89-3.81L17.08 39a2.8 2.8 0 0 0 1.55 4.49h.55a2.8 2.8 0 0 0 2.44-4.07");
}

</style>
