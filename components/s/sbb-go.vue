<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z_i8820zz"/><circle class="cpk0fnbgt"/><path class="wilolibni"/><path class="x-m42_btl"/><path class="ixngrwb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbb-go" /></template>
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

.ixngrwb6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.273 31.416v-.224a1.324 1.324 0 0 1 1.324-1.324a1.324 1.324 0 0 1 1.324 1.324v3.915l-.002 1.38a7.7 7.7 0 0 1-1.268 4.922H21.33l-5.036-8.215a1.45 1.45 0 0 1 .321-1.88a1.45 1.45 0 0 1 1.992.157l2.723 3.04m-2.003-8.114a3.786 3.786 0 0 1 3.147-5.72A3.786 3.786 0 0 1 28.63 25");
}

.wilolibni {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.421 15.318h39.158M21.33 34.51v-9.862a1.324 1.324 0 0 1 1.323-1.324a1.324 1.324 0 0 1 1.324 1.324v6.768m0 0v-8.222a1.324 1.324 0 0 1 1.324-1.324a1.324 1.324 0 0 1 1.324 1.324v8.222");
}

.x-m42_btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.625 31.416v-1.771a1.324 1.324 0 0 1 1.324-1.324a1.324 1.324 0 0 1 1.324 1.324v1.77");
}

.z_i8820zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.87 6.041l2.865 2.868l-2.867 2.867m-5.739 0L18.265 8.91l2.867-2.868m-2.867 2.867h11.47M24 6.041v5.736");
}

</style>
