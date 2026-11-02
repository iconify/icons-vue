<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ioannv8yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:utensils-round" /></template>
<style>
.ioannv8yz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 14V3a5 5 0 0 0-5 5v2a4 4 0 0 0 4 4zm0 0v7M3 3v4a4 4 0 1 0 8 0V3M7 3v18");
}

</style>
