<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfjcnqkee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plant-support-ring" /></template>
<style>
.hfjcnqkee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5V7m0 2C9 9 6.5 7 6.5 4c3 0 5.5 2 5.5 5m0-2c0-2.5 2.5-4.5 5.5-4.5C17.5 5 15 7 12 7m-8 8a8 2.5 0 1 0 16 0a8 2.5 0 1 0-16 0m15.5 0v6.5");
}

</style>
