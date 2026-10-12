<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7cum3b1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pet-bowl-clock" /></template>
<style>
.c7cum3b1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 14h17.5l-1.6 5.75a2 2 0 0 1-1.9 1.5H6.75a2 2 0 0 1-1.9-1.5ZM8.7 7.5h6.6a1.75 1.75 0 1 1 2.75 1a1.75 1.75 0 1 1-2.75 1H8.7a1.75 1.75 0 1 1-2.75-1a1.75 1.75 0 1 1 2.75-1");
}

</style>
