<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uukccmbph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shoe-fitting-bench" /></template>
<style>
.uukccmbph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.5h16.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 20.25 18H3.75a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25M5 18v3.5M19 18v3.5m-15-6v-10h4c1 2.5 3 3.5 5.5 4l5 1c1.5.25 2.5 1.5 2.5 3v2M4 12.75h17M9.5 7.5l-1 1.75m3.75-.5l-.75 1.5");
}

</style>
