<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j84jy6bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:steam-room" /></template>
<style>
.j84jy6bpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19m-19 3h19M5 18v3.5M19 18v3.5M7 12c-1.25-1.5 1.25-3 0-4.5s1.25-3 0-4.5m5 9c-1.25-1.5 1.25-3 0-4.5s1.25-3 0-4.5m5 9c-1.25-1.5 1.25-3 0-4.5s1.25-3 0-4.5");
}

</style>
