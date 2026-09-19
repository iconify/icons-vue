<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v6qk-nn3s"/><circle class="cpk0fnbgt"/><circle class="vqogbbbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:math-wiki" /></template>
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

.v6qk-nn3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.68 24h-2.15m5.817 0h-2.15m5.818 0h-2.15m5.817 0h-2.15M21.47 24h-2.15m-1.517 0h-2.15m-1.518 0h-2.15m-1.517 0h-2.15M24 15.653v2.15m0 1.517v2.15m0 5.06v2.15m0 1.517v2.15m0 1.518v2.15m0 1.517v2.15m0-27.697v2.15m0-5.817v2.15M10.341 20.712c21.753-22.133 15.177 12.9 27.57 15.682");
}

.vqogbbbht {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
