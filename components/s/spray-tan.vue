<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzsx5ubyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spray-tan" /></template>
<style>
.mzsx5ubyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 9h2.75a2.625 2.625 0 0 1 2.625 2.625v7.25A2.625 2.625 0 0 1 8.875 21.5h-2.75A2.625 2.625 0 0 1 3.5 18.875v-7.25A2.625 2.625 0 0 1 6.125 9M5 9V5.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1V9m4-5l3.5-1.5M14 6.75h4.5M14 9.5l3.5 1.5M16 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-3.75h.01M21.75 18h.01M18 21.75h.01M14.25 18h.01m6.49-2.75h.01m-.01 5.5h.01m-5.51 0h.01m-.01-5.5h.01");
}

</style>
