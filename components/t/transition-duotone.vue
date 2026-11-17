<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mnyoa3bex"/><path class="slox3ncxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transition-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mnyoa3bex {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 18a2 2 0 1 1 3.999-.001A2 2 0 0 1 4 18m12 0a2 2 0 1 1 3.999-.001A2 2 0 0 1 16 18");
}

.slox3ncxr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m12 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M6 12v-2a6 6 0 1 1 12 0v2m-3-3l3 3l3-3");
}

</style>
