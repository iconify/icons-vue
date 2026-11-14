<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tl05wpb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microspikes" /></template>
<style>
.tl05wpb8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15.5V4h6v5.5l6.5 1.5c2.25.5 3.5 2 3.5 4.5Zm.5 0L6 19l1.5-3.5L9 19l1.5-3.5L12 19l1.5-3.5L15 19l1.5-3.5L18 19l1.5-3.5M15 10.75l-1.5 4.75");
}

</style>
