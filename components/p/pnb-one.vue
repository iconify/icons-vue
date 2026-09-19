<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ahdekacqg"/><circle class="rguz-mbtj"/><path class="kgg-4sbwt"/><path class="uo47pyvli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pnb-one" /></template>
<style>
.ahdekacqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.487 26.247v-8.813l5.839 8.813v-8.813m1.767 4.406h2.873m1.534 4.407h-4.407v-8.813H38.5");
}

.kgg-4sbwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.326 34.566V28h-6.241a8.525 8.525 0 0 1-15.573-4.798V20.05c0-2.162-1.012-2.615-1.012-2.615");
}

.rguz-mbtj {
  cx: 19.037px;
  cy: 23.202px;
  r: 5.768px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

</style>
