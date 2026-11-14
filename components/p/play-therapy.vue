<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3dl9qe3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:play-therapy" /></template>
<style>
.d3dl9qe3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12h2A1.75 1.75 0 0 1 8 13.75v2a1.75 1.75 0 0 1-1.75 1.75h-2a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 4.25 12m5.5 0h2a1.75 1.75 0 0 1 1.75 1.75v2a1.75 1.75 0 0 1-1.75 1.75h-2A1.75 1.75 0 0 1 8 15.75v-2A1.75 1.75 0 0 1 9.75 12M7 6.5h2a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 9 12H7a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 7 6.5m9.25 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
