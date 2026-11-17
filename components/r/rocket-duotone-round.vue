<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mnmd_bbia"/><path class="k_k89z8xq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocket-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k_k89z8xq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 12l2-4c2-4 6-5 10-5c0 4-1 8-5 10l-4 2Zm0 0H5c0-2 1-4 3-4h3m1 7v4c2 0 4-1 4-3v-3M3 21c1 0 4 0 5-1a2.828 2.828 0 1 0-4-4c-1 1-1 4-1 5");
}

.mnmd_bbia {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 12c.001-1.815.881-3.998 3-4h3c1.974-3.941 5.899-4.999 10-5c-.001 4.101-1.059 8.026-5 10v3c-.002 2.119-2.185 2.999-4 3v-4l-3-3Zm-2 9c0-1.321.04-4.038 1-5a2.828 2.828 0 1 1 4 4c-.962.96-3.679 1-5 1");
}

</style>
