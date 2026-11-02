<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cia03h47k"/><path class="sfj3jr60e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-duotone-round" /></template>
<style>
.cia03h47k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 12V5a3.001 3.001 0 0 1 5-2.236A3 3 0 0 1 9 2h8c1.309 0 2.675.525 3.458 1.613c.258.355.436.761.523 1.191l1 5Q22 9.901 22 10v1a4 4 0 0 1-4 4h-1a.997.997 0 0 0-1 1v3a3 3 0 1 1-6 0v-1a3 3 0 0 0-3-3H5a3 3 0 0 1-3-3");
}

.ft5dv1b6b {
  fill: none;
}

.sfj3jr60e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-3a2 2 0 0 1 2-2h1a3 3 0 0 0 3-3v-1l-1-5c-.233-1.163-1.488-2-3-2H9a2 2 0 0 0-2 2m0 9H5a2 2 0 0 1-2-2V5a2 2 0 1 1 4 0z");
}

</style>
