<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jy8rz_due"/><path class="ar5qe8n4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-left-duotone-round" /></template>
<style>
.ar5qe8n4p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a6 6 0 0 1 6-6h6a6 6 0 1 1 0 12H9a6 6 0 0 1-6-6m3 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.jy8rz_due {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6h6a6 6 0 1 1 0 12H9A6 6 0 1 1 9 6m0 9a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
