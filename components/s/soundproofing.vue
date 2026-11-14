<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e022up45g"/><path class="g_wmc9bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soundproofing" /></template>
<style>
.e022up45g {
  d: path("M5.125 2.5h13.75A2.625 2.625 0 0 1 21.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5");
}

.g_wmc9bjh {
  d: path("m5 7.75l1.75-2.5l1.75 2.5l1.75-2.5L12 7.75l1.75-2.5l1.75 2.5l1.75-2.5L19 7.75M6.75 13l1.75-2.5l1.75 2.5L12 10.5l1.75 2.5l1.75-2.5l1.75 2.5M5 18.25l1.75-2.5l1.75 2.5l1.75-2.5l1.75 2.5l1.75-2.5l1.75 2.5l1.75-2.5l1.75 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
