<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ruvcqwbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tourniquet-sharp" /></template>
<style>
.ruvcqwbyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.81 16.24l5.3-5.3m2.83-2.83l5.3-5.3M7.76 21.19l5.3-5.3m2.83-2.83l5.3-5.3M7.41 8.82l1.41-1.41l.71-.71l.71.71l6.88 6.89l.71.71l-.71.71l-1.4 1.4l-.71.71l-.71-.71l-6.89-6.88l-.71-.71zm.7-.71L5.99 5.99M3.34 4.4L4.4 3.34l.53-.53l.53.53L6.52 4.4l.53.53l-.53.53l-1.06 1.06l-.53.53l-.53-.53l-1.06-1.06l-.53-.53z");
}

</style>
