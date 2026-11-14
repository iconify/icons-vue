<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yra0r9b2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:phone-pause" /></template>
<style>
.yra0r9b2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 3.5c.8 0 1.3.5 1.5 1.25l.75 3c.15.75-.15 1.35-.75 1.75l-1.5 1c1.2 2.5 2.4 3.8 5 5l1-1.5c.4-.6 1-.9 1.75-.75l3 .75c.75.2 1.25.7 1.25 1.5v3c0 1.1-.9 2-2 2c-8 0-15-7-15-15c0-1.1.9-2 2-2Zm7.5.25v5.5m3.75-5.5v5.5");
}

</style>
