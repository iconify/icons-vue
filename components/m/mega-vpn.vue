<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a1f0xyb1o"/><path class="i54y-9bxi"/><circle class="gtg64fbbu"/><path class="ebadz0bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mega-vpn" /></template>
<style>
.a1f0xyb1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.15 5.45C16.33 3.57 20.04 2.5 24 2.5c11.87 0 21.5 9.63 21.5 21.5S35.87 45.5 24 45.5S2.5 35.87 2.5 24c0-3.96 1.07-7.67 2.95-10.85");
}

.ebadz0bqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.198 12.798l2.4-3h-3.6l2.4-3");
}

.gtg64fbbu {
  cx: 9.798px;
  cy: 9.798px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.i54y-9bxi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.5 31.483V16.5l10.5 15l10.5-14.977V31.5");
}

</style>
