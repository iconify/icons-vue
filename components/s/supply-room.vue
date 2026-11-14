<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9qbmwbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:supply-room" /></template>
<style>
.w9qbmwbuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5v19m16-19v19M4 9.5h16m-16 7h16M8.5 4.5h2A1.5 1.5 0 0 1 12 6v2a1.5 1.5 0 0 1-1.5 1.5h-2A1.5 1.5 0 0 1 7 8V6a1.5 1.5 0 0 1 1.5-1.5m7.625 2zA1.375 1.375 0 0 1 17.5 7.875v.25A1.375 1.375 0 0 1 16.125 9.5a1.375 1.375 0 0 1-1.375-1.375v-.25A1.375 1.375 0 0 1 16.125 6.5M10 12h4a1.5 1.5 0 0 1 1.5 1.5V15a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 15v-1.5A1.5 1.5 0 0 1 10 12");
}

</style>
