<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h28czlhka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tax-hand" /></template>
<style>
.h28czlhka {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m3.75-1.25v2.5M3 13.5V21m2.5-6.5H9c1.25 0 2.25.5 3 1.25h2.5a1.5 1.5 0 0 1 0 3h-4m4.25-.5l4.5-2.75A1.5 1.5 0 0 1 21 18l-5.5 3.25h-10");
}

</style>
