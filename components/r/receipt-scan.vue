<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2mx4oywo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:receipt-scan" /></template>
<style>
.i2mx4oywo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m6-9h5A1.5 1.5 0 0 1 16 8.5v7.882A.69.69 0 0 1 15 17l-.329-.165a1.5 1.5 0 0 0-1.342 0l-.658.33a1.5 1.5 0 0 1-1.342 0l-.658-.33a1.5 1.5 0 0 0-1.342 0L9 17a.69.69 0 0 1-1-.618V8.5A1.5 1.5 0 0 1 9.5 7m1 3h3m-3 3h3");
}

</style>
