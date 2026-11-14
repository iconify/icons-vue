<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hftt8nbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:props-table" /></template>
<style>
.hftt8nbje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19M5 14l-1 7m15-7l1 7m-2.5-11H8a2 2 0 0 0 0 4h9.5Zm-7.25-7h4A1.75 1.75 0 0 1 16 4.75v3.5A1.75 1.75 0 0 1 14.25 10h-4A1.75 1.75 0 0 1 8.5 8.25v-3.5A1.75 1.75 0 0 1 10.25 3m2 0v3");
}

</style>
