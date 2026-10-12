<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1j3ima_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pudding" /></template>
<style>
.w1j3ima_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6.75h5.5q1.25 0 1.55 1.21l2.15 8.83q.3 1.21-.95 1.21h-11q-1.25 0-.95-1.21L7.7 7.96Q8 6.75 9.25 6.75M6.6 10.5h10.8M3 21h18");
}

</style>
