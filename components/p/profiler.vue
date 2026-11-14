<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0zbw2bkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:profiler" /></template>
<style>
.y0zbw2bkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 16.75h15.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 19v-.5a1.75 1.75 0 0 1 1.75-1.75m0-6.75h7.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 11.75 14h-7.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 4.25 10M18 10h1.75a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 19.75 14H18a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 18 10M7 3.25h2.5A1.75 1.75 0 0 1 11.25 5v.5A1.75 1.75 0 0 1 9.5 7.25H7A1.75 1.75 0 0 1 5.25 5.5V5A1.75 1.75 0 0 1 7 3.25");
}

</style>
