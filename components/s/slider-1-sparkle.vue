<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns0l6-ggr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-sparkle" /></template>
<style>
.ns0l6-ggr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 6h2m4 0h2M3 18h8m4 0h6M18 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
