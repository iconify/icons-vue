<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3x5ekb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seated-mode" /></template>
<style>
.e3x5ekb5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3h11A2.5 2.5 0 0 1 19 5.5V7a2.5 2.5 0 0 1-2.5 2.5h-3L12 8l-1.5 1.5h-5A2.5 2.5 0 0 1 3 7V5.5A2.5 2.5 0 0 1 5.5 3m1.75 6.5l1.25 5.75v6.25m0-6.25H19v6.25");
}

</style>
