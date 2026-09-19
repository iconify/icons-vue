<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hpcsyhdcg"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nrc" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hpcsyhdcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.38 25.37a3 3 0 0 1-2.94 2.57h0a3 3 0 0 1-3-3V23a3 3 0 0 1 3-3h0a3 3 0 0 1 2.93 2.56M9.35 23a3 3 0 0 1 3-3h0a3 3 0 0 1 3 3v4.92m-6-7.86v7.88M18.49 23a3 3 0 0 1 3-3h0m-3 .06v7.88m14.69-7.88L38.65 24l-5.47 3.94L34.61 24z");
}

</style>
