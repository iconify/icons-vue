<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6myjgbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mothers-day-flower" /></template>
<style>
.w6myjgbhq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5a1.75 1.75 0 0 1 3.5 0A1.75 1.75 0 0 1 12 5a1.75 1.75 0 0 1 3.5 0A1.75 1.75 0 0 1 19 5c0 4-3 6-7 6S5 9 5 5m7 6v9.5m0-3c.5-3 3.5-4.5 6.5-4c-.5 3-3.5 4.5-6.5 4");
}

</style>
