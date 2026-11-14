<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsqp30mrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mesh-system" /></template>
<style>
.jsqp30mrj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m12 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5-8.25l-4 6.5m6-6.5l4 6.5M8 18h8M8.75 4.75a4.5 4.5 0 0 1 6.5 0m-13 11a4.5 4.5 0 0 1 3-2.25m13.5 0a4.5 4.5 0 0 1 3 2.25");
}

</style>
