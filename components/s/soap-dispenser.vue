<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kkj1ty9lj"/><path class="rgvj1gbhn"/><path class="g9pfrpbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soap-dispenser" /></template>
<style>
.g9pfrpbgp {
  d: path("M8 7.5h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkj1ty9lj {
  d: path("M3.75 3zA1.25 1.25 0 0 1 5 4.25v10.5A1.25 1.25 0 0 1 3.75 16a1.25 1.25 0 0 1-1.25-1.25V4.25A1.25 1.25 0 0 1 3.75 3M8.5 4h5A3.5 3.5 0 0 1 17 7.5v3a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 5 10.5v-3A3.5 3.5 0 0 1 8.5 4M17 8.5h2.75c1 0 1.75.75 1.75 1.75V12m-12 2v1.5");
}

.rgvj1gbhn {
  fill: currentColor;
  d: path("M9.5 17c1 1.25 1.75 2.25 1.75 3c0 1-.75 1.5-1.75 1.5S7.75 21 7.75 20c0-.75.75-1.75 1.75-3");
}

</style>
