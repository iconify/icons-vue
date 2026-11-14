<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-lk2pmzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spatial-call" /></template>
<style>
.h-lk2pmzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M2.5 20c0-3 1.75-5 4-5s4 2 4 5M15 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M13.5 20c0-3 1.75-5 4-5s4 2 4 5M7.179 4.255a7.5 7.5 0 0 1 3.519-1.641m2.604 0a7.5 7.5 0 0 1 3.519 1.641");
}

</style>
