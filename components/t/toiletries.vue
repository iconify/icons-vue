<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di1gmkbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:toiletries" /></template>
<style>
.di1gmkbkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 9za3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 7.5 21A3.5 3.5 0 0 1 4 17.5v-5A3.5 3.5 0 0 1 7.5 9M7 5.5h1A1.5 1.5 0 0 1 9.5 7v.5A1.5 1.5 0 0 1 8 9H7a1.5 1.5 0 0 1-1.5-1.5V7A1.5 1.5 0 0 1 7 5.5m9.75 6.5zA3.25 3.25 0 0 1 20 15.25v2.5A3.25 3.25 0 0 1 16.75 21a3.25 3.25 0 0 1-3.25-3.25v-2.5A3.25 3.25 0 0 1 16.75 12m0 0V9h2.75");
}

</style>
