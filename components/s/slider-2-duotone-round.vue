<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dpolj7ivh"/><path class="cshijd3wh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-2-duotone-round" /></template>
<style>
.cshijd3wh {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m6 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-8 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 6h5m4 0h9M3 12h11m4 0h3M3 18h3m4 0h11");
}

.dpolj7ivh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 8a2 2 0 1 1-.001-3.999A2 2 0 0 1 10 8m6 6a2 2 0 1 1-.001-3.999A2 2 0 0 1 16 14m-8 6a2 2 0 1 1-.001-3.999A2 2 0 0 1 8 20");
}

.ft5dv1b6b {
  fill: none;
}

</style>
