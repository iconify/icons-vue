<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="gq1_plbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:samsung-portable-ssd" /></template>
<style>
.gq1_plbpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.198 27.904c.613.798 1.382 1.095 2.451 1.095h1.48a2.494 2.494 0 0 0 2.495-2.494v-.011A2.494 2.494 0 0 0 16.13 24h-1.633A2.497 2.497 0 0 1 12 21.503h0a2.5 2.5 0 0 1 2.502-2.502h1.472c1.07 0 1.839.297 2.452 1.095m2.46 7.808c.613.798 1.382 1.095 2.452 1.095h1.48a2.494 2.494 0 0 0 2.494-2.494v-.011A2.494 2.494 0 0 0 24.818 24h-1.633a2.497 2.497 0 0 1-2.497-2.497h0a2.5 2.5 0 0 1 2.502-2.502h1.473c1.07 0 1.838.297 2.451 1.095m2.262 8.903V19h2.25A4.374 4.374 0 0 1 36 23.375v1.25a4.374 4.374 0 0 1-4.374 4.374z");
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
