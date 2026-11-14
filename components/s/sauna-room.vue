<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbbkg0ctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sauna-room" /></template>
<style>
.qbbkg0ctz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.982 9h8.036a1.75 1.75 0 0 1 1.736 1.967l-1.062 8.5A1.75 1.75 0 0 1 12.955 21h-5.91a1.75 1.75 0 0 1-1.737-1.533l-1.062-8.5A1.75 1.75 0 0 1 5.982 9M11.5 9l8-6.5M4.5 13h11M5 17.25h10");
}

</style>
