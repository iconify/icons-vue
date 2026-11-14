<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gv8ma0bbv"/><path class="p7aopl4yf"/><path class="ti4fftb2w"/><path class="iybklwb-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skin-tone" /></template>
<style>
.gv8ma0bbv {
  fill: currentColor;
  d: path("M2 12a3.25 3.25 0 1 0 6.5 0A3.25 3.25 0 1 0 2 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iybklwb-w {
  d: path("M15.5 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.p7aopl4yf {
  fill: currentColor;
  d: path("M6.5 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.ti4fftb2w {
  d: path("M11 12a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
