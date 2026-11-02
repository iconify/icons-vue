<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l-8ocqb_t"/><path class="p1d--d9px"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podium-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l-8ocqb_t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 7a3 3 0 0 1 3-3h4a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1Z");
}

.p1d--d9px {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 12H5a2 2 0 0 0-2 2v3a4 4 0 0 0 4 4h1m8-6h3a2 2 0 0 1 2 2v1a3 3 0 0 1-3 3h-2m-8 0V7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v14zm3-10l2-2v6");
}

</style>
