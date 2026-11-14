<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unkxvrhwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prom" /></template>
<style>
.unkxvrhwv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 6.5q2.5 1.5 5 0l-1 4.5q2 5.5 6 8.75q-7.5 3-15 0q4-3.25 6-8.75Zm0 0L9.75 3m4.75 3.5L14.25 3m-3.75 8h3M19 2.75Q19 5 21.25 5Q19 5 19 7.25Q19 5 16.75 5Q19 5 19 2.75");
}

</style>
