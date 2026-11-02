<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luemuubgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-2" /></template>
<style>
.luemuubgo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-8 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 6h5m4 0h9M3 12h11m4 0h3M3 18h3m4 0h11");
}

</style>
