<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ap6fg00yg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:poll-anonymous" /></template>
<style>
.ap6fg00yg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h13a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-13a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 6.75h7a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2a2 2 0 0 1 2-2m0 6.75h3a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2a2 2 0 0 1 2-2m10 1.5c1.25-2 2.5-2.75 3.5-2.75s2.25.75 3.5 2.75c-1.25 2-2.5 2.75-3.5 2.75S15.75 20 14.5 18m.5 3.5l6-7");
}

</style>
