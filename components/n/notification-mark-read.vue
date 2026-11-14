<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx_3vk6xg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:notification-mark-read" /></template>
<style>
.sx_3vk6xg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 15V9.5a5.5 5.5 0 0 1 11 0V15m-13 0h15M10 2.5V4M8.75 18a1.25 1.25 0 0 0 2.5 0m3.5 0l2 2L21 15.75");
}

</style>
