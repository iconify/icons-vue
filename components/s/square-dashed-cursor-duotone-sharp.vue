<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cyx0i9j4i"/><path class="q4zaa2bdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-duotone-sharp" /></template>
<style>
.cyx0i9j4i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21.316 12.051a1 1 0 0 1-.073 1.919l-2.287.572l1.751 1.751a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-1.751-1.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265Z");
}

.ft5dv1b6b {
  fill: none;
}

.q4zaa2bdd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6V3h3m12 0h3v3M6 21H3v-3m7-15h4M3 14v-4m6-1l12 4l-4 1l3 3l-3 3l-3-3l-1 4z");
}

</style>
