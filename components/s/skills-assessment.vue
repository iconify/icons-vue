<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-m1foy8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skills-assessment" /></template>
<style>
.m-m1foy8e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 3 5m5.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M3 11a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 3 11m5.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M3 17a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 3 17m5.25 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M4.75 5h.01M10 11h.01m-5.26 6h.01M20.891 3.045za1.25 1.25 0 0 1 .884 1.531l-3.079 11.491a1.5 1.5 0 0 1-.326.607l-.693.78a.699.699 0 0 1-1.207-.323l-.209-1.022a1.5 1.5 0 0 1 .02-.689L19.36 3.929a1.25 1.25 0 0 1 1.531-.884m-2.113 3.057l2.415.647");
}

</style>
