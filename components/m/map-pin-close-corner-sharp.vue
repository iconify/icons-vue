<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csushacwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-close-corner-sharp" /></template>
<style>
.csushacwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5M8 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 5l6 6m0-6l-6 6");
}

</style>
