<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8ne9bcji"/><path class="y1v17lbad"/><path class="j5vfo0g6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tic-80" /></template>
<style>
.j5vfo0g6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.48 30.61c-2.64 3.96-7.93 3.96-10.57 0m0-13.22v5.29m10.57-5.29v5.29m6.61 3.96H8.3V10.78h23.79zM8.3 39.86h7.93m7.93 0h7.93M8.3 8.14h26.43");
}

.o8ne9bcji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.34 17.39c0 6.17-1.32 8.81-3.96 7.93");
}

.y1v17lbad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.3 42.5h7.93v-2.64h7.93v2.64h7.93v-2.64h2.64v-2.64h2.64l.04-3.98l-.04-3.95V8.14h-2.64V5.5H8.3v2.64H5.66v31.71H8.3v2.64Z");
}

</style>
