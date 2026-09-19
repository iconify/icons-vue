<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="z9e2i7b1r"/><path class="cli61mpvo"/><path class="vsekpdbjp"/><path class="ed-kubcpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifiman" /></template>
<style>
.cli61mpvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.19 32.535c5.34-1.347 11.384-2.135 10.953-8.05c4.861 4.474 8.42-.812 12.357-3.277m-12.358 3.276c-5.603-3.4-9.165-.477-11.607 2.06c.095 1.307 3.285.099 6.272-.281");
}

.ed-kubcpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.5 19.955c6.212-5.72 13.556-7.022 21.155-1.18");
}

.vsekpdbjp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.473 19.25a3.427 3.427 0 1 1-.055-.112M6.716 23.464a10.59 10.59 0 0 1 14.802-1.273M9.99 26.621a6.15 6.15 0 0 1 8.113-1.2");
}

.z9e2i7b1r {
  cx: 14.953px;
  cy: 31.01px;
  r: 2.01px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
