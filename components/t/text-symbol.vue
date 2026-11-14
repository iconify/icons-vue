<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0me_yy0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:text-symbol" /></template>
<style>
.g0me_yy0y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 20h4.5v-2C5.75 16.75 4 14.25 4 11.25C4 7 7.5 4 12 4s8 3 8 7.25c0 3-1.75 5.5-4.5 6.75v2H20");
}

</style>
