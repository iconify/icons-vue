<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzg55o8gi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-headset-round" /></template>
<style>
.lzg55o8gi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 10a4 4 0 1 0 8 0a4 4 0 0 0-8 0M4 21c0-2.21 3.582-4 8-4s8 1.79 8 4M5 10a7 7 0 0 1 14 0M5 10H4a1 1 0 0 0-1 1v2a1 1 0 0 0 2 0zm14 0h1a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0zm1 4a1 1 0 0 1-1 1h-1");
}

</style>
