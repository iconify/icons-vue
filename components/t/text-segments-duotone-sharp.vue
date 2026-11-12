<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="z2c-33v2d"/><path class="pdfj1qbdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-segments-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pdfj1qbdz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 5h7v5H3Zm0 9h10v5H3Zm11-9h7v5h-7Zm3 9h4v5h-4Z");
}

.z2c-33v2d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm11 0a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm-8 9a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Zm8 0a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Z");
}

</style>
