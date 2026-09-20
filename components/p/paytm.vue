<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qp9x0sbbl"/><path class="hgtsdt1ut"/><path class="ms4yy948e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paytm" /></template>
<style>
.hgtsdt1ut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.557 23.534v-7.992l4 8l4-7.987v7.987m-31.424 0v-8h2.619c1.48 0 2.68 1.203 2.68 2.687s-1.2 2.687-2.68 2.687h-2.62m16.516-5.374h5.3m-2.65 8v-8m-2.65 6.216v2.7a2 2 0 0 1-2 2a2 2 0 0 1-1.414-.586");
}

.ms4yy948e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.648 18.458v3.3a2 2 0 1 1-4 0v-3.3m-1.906 3.064a2 2 0 1 1-4 0v-1.3a2 2 0 1 1 4 0m0 3.3v-5.3");
}

.qp9x0sbbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4zm0 12.9h37m-37-3.033h37");
}

</style>
