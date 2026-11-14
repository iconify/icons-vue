<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqz4w_ztu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:weather-sensor-farm" /></template>
<style>
.nqz4w_ztu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V8M4.5 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m11 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7 0h7m-4.25 6h1.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 11.25 12m-7 8.25v-2.5m0 .75c-.05-1.32-.93-2.02-2.25-2c-.08 1.2.8 1.9 2.25 2m0-.75c-.05-1.45.82-2.5 2.25-2.5c-.03 1.4-.9 2.45-2.25 2.5M3 21h18");
}

</style>
