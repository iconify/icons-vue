<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l2mqttbmy"/><circle class="njmf6ne0q"/><path class="r208b4b5u"/><path class="k58zh0cup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myswordforandroid" /></template>
<style>
.k58zh0cup {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.82 32.21l21.9-23.06l7.74-3.33l-3.47 7.68l-23.45 21.48");
}

.l2mqttbmy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.32 28.52l-9.74-9.74a1.66 1.66 0 0 1 0-2.35L17 6a1.66 1.66 0 0 1 2.35 0l9.42 9.41m3.9 3.88l9.77 9.76a1.66 1.66 0 0 1 0 2.35L32 41.84a1.66 1.66 0 0 1-2.35 0L19.32 31.52M8.61 20.81l12.8-12.79m6.03 31.62l12.79-12.79M11.58 14.67l3.69-3.69");
}

.njmf6ne0q {
  cx: 10.06px;
  cy: 16.19px;
  r: 0.65px;
  fill: currentColor;
}

.r208b4b5u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.84 27.07l.09 2.2l8.39 8.55l2.31.24m-6.45-4.47l-8.03 7.89m-1-1.02l2 2.04");
}

</style>
