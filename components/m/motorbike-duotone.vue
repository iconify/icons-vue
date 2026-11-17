<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ys6b0fuzz"/><path class="bdniwqb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:motorbike-duotone" /></template>
<style>
.bdniwqb0w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0m12 0a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0m-6 0h2a1 1 0 0 0 1-1a5 5 0 0 1 5-5a1 1 0 0 0 1-1m0 4V8a2 2 0 0 0-2-2M3 10l6 2a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v1");
}

.ft5dv1b6b {
  fill: none;
}

.ys6b0fuzz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 12a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v1Zm-6 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m12 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-9 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2m12 0a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
