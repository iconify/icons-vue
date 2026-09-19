<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h-rvjhw6i"/><circle class="voo0n1byh"/><path class="pzyumxcmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:meteoswiss" /></template>
<style>
.h-rvjhw6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.46 22.69A7.21 7.21 0 0 0 9.57 26.9a6.45 6.45 0 0 0-5.07 6.3c0 2.74 1.64 6.46 6.92 6.46h17a5.05 5.05 0 0 0 4.46-7.44");
}

.pzyumxcmh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.41 11.34v5.29m9.26-1.46l-3.74 3.74m7.57 5.52h-5.29m1.46 9.25l-3.74-3.74M21.16 15.17l3.74 3.74m-15.95-3.2v-4.77m-2.39 2.39h4.78M9 18.89c4.71-1.81 4.47-5.42 4.44-7.6V9.65A16.8 16.8 0 0 0 9 8.89a16.8 16.8 0 0 0-4.44.76s0 1.22 0 1.64c-.08 2.18-.32 5.79 4.44 7.6");
}

.voo0n1byh {
  cx: 30.41px;
  cy: 24.43px;
  r: 6.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
