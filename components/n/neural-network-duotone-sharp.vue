<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bfbw-tbux"/><path class="y6yqvjb5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:neural-network-duotone-sharp" /></template>
<style>
.bfbw-tbux {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 8a2 2 0 1 1-.001-3.999A2 2 0 0 1 6 8m12 0a2 2 0 1 1-.001-3.999A2 2 0 0 1 18 8M6 20a2 2 0 1 1-.001-3.999A2 2 0 0 1 6 20m12 0a2 2 0 1 1-.001-3.999A2 2 0 0 1 18 20");
}

.ft5dv1b6b {
  fill: none;
}

.y6yqvjb5m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0M8 6h8M8 18h8M8 8l8 8m-8 0l8-8m0-2a2 2 0 1 0 4 0a2 2 0 0 0-4 0m0 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
