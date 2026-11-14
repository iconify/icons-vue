<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="drxu1ilga"/><path class="f5_lid89u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mountain-home" /></template>
<style>
.drxu1ilga {
  d: path("M2.5 14L12 2.5L21.5 14m-17-2.5v10m15-10v10m-17 0h19m-19-5h19");
}

.f5_lid89u {
  d: path("M13.125 8.25zA1.136 1.136 0 0 1 12.17 10h-.34a1.136 1.136 0 0 1-.955-1.75a1.337 1.337 0 0 1 2.25 0M10.5 21.5V19h3v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
