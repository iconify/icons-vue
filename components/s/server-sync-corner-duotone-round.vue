<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x_cv33b3z"/><path class="f5m5a5bsz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-sync-corner-duotone-round" /></template>
<style>
.f5m5a5bsz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m6 13H6a3 3 0 0 1 0-6h3M7 7h.01M7 17h.01M21 19a4.472 4.472 0 0 1-8 0m3 0h-3v3m0-6a4.472 4.472 0 0 1 8 0m-3 0h3v-3");
}

.ft5dv1b6b {
  fill: none;
}

.x_cv33b3z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6m3 16H6a3 3 0 1 1 0-6h3Z");
}

</style>
