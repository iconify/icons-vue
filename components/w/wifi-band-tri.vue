<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qtvpbdc_q"/><path class="ol1xhlbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wifi-band-tri" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ol1xhlbcb {
  d: path("M5 11.5a7.5 7.5 0 0 1 12 0m-9 2.25a3.75 3.75 0 0 1 6 0M11 16h.01m5.49-.5H21l-2 2a2 2 0 1 1-1.5 3.5");
}

.qtvpbdc_q {
  d: path("M2 9.25a11.25 11.25 0 0 1 18 0");
}

</style>
