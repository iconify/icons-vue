<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k5183ok-g"/><path class="q4tj-pt1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:potted-plant-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k5183ok-g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 9v2a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3v-1H9a6 6 0 0 1-6-6V3h3a6 6 0 0 1 6 6m5 7v3a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-3Z");
}

.q4tj-pt1s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16h10v3a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm5 0V9m0 0a6 6 0 0 0-6-6H3v2a6 6 0 0 0 6 6h3Zm0 2a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3Z");
}

</style>
