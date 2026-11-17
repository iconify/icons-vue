<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p331h_bjg"/><path class="f4jvdiboh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:water-heater-duocolor-round" /></template>
<style>
.f4jvdiboh {
  d: path("M6 10a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v7a4 4 0 0 1-4 4h-4a4 4 0 0 1-4-4Zm3-7v3m6-3v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p331h_bjg {
  stroke-opacity: 0.4;
  d: path("M12 9c.25 1.25 1 2.25 2 3c.75.75 1 1.75 1 3a3 3 0 1 1-6 0c0-.75.25-1.25.5-1.5m0 0a1 1 0 1 0 2 0c0-.75-.25-1-.5-1.5c-.5-1-.25-2 1-3");
}

</style>
