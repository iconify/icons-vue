<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cp1muvb_r"/><path class="h56ogjbph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microscope-duotone" /></template>
<style>
.cp1muvb_r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 5V4a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v1a1 1 0 0 1 1 1v5a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V6a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.h56ogjbph {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 6h6v5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm1 0V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2M3 21h18M6 17h8m0 4a6 6 0 0 0 6-6a5 5 0 0 0-5-5h-2");
}

</style>
