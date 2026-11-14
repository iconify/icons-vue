<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2u2d5b3w"/><path class="i7wdyb1gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-alert-tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7wdyb1gk {
  d: path("M11.75 11h.5A4.75 4.75 0 0 1 17 15.75a4.75 4.75 0 0 1-4.75 4.75h-.5A4.75 4.75 0 0 1 7 15.75A4.75 4.75 0 0 1 11.75 11m.25 2.25v5m-2.5-2.5h5");
}

.n2u2d5b3w {
  d: path("M7 14.25c-2.75-1-4.5-2.75-4.5-4.75c0-3.25 4.25-6 9.5-6s9.5 2.75 9.5 6c0 2-1.75 3.75-4.5 4.75");
}

</style>
