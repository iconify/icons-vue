<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hz8nbsx5u"/><path class="w8vy4_cmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:refraction-light" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hz8nbsx5u {
  d: path("M2.5 11h19m-18-8l7.5 8l3 9.5");
}

.w8vy4_cmc {
  d: path("M15.25 17.75L14 20.5L11.5 19");
}

</style>
