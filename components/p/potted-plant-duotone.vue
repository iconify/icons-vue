<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h327n3bic"/><path class="q4tj-pt1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:potted-plant-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h327n3bic {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.57 6.58A6.98 6.98 0 0 1 18 4h3a1 1 0 0 1 1 1v1a7 7 0 0 1-7 7h-3a1 1 0 0 1-1-1H9a7 7 0 0 1-7-7V3a1 1 0 0 1 1-1h3a7.01 7.01 0 0 1 6.57 4.58M18 16v3a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3v-3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1");
}

.q4tj-pt1s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 16h10v3a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm5 0V9m0 0a6 6 0 0 0-6-6H3v2a6 6 0 0 0 6 6h3Zm0 2a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3Z");
}

</style>
