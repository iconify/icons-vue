<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ucqmhwbva"/><path class="kazrtko-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smartwatch-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kazrtko-r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Zm3-4V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1M9 18v1a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-1");
}

.ucqmhwbva {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 5h4a5 5 0 0 1 5 5v4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 14 19h-4a5 5 0 0 1-5-5v-4a5 5 0 0 1 5-5");
}

</style>
