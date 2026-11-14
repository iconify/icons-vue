<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szskb2bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soap-bar" /></template>
<style>
.szskb2bje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12.5h9A4.5 4.5 0 0 1 21 17a4.5 4.5 0 0 1-4.5 4.5h-9A4.5 4.5 0 0 1 3 17a4.5 4.5 0 0 1 4.5-4.5M5 7.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10.75 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m3.5 3.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 16h4");
}

</style>
