<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sq07x-bkh"/><path class="hnr85p9pe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:trampoline-park" /></template>
<style>
.hnr85p9pe {
  d: path("M7.5 5L12 8.5L16.5 5M9 11.25l3-2.75l3 2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sq07x-bkh {
  d: path("M2 16.5a10 2.5 0 1 0 20 0a10 2.5 0 1 0-20 0m4 2v3m12-3v3m-7.5-18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
