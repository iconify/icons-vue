<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q84k_lbqk"/><path class="p2tl7ubfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suspension-railway-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p2tl7ubfb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20H5a2 2 0 0 1-2-2v-6a3 3 0 0 1 3-3h11l4 4v5a2 2 0 0 1-2 2zm-9-4h18M11 9v7M3 4h18M7 4v5m8-5v5");
}

.q84k_lbqk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 21a3 3 0 0 1-3-3v-6a4 4 0 0 1 4-4h11c.265 0 .52.105.707.293l4 4A1 1 0 0 1 22 13v5a3 3 0 0 1-3 3Z");
}

</style>
