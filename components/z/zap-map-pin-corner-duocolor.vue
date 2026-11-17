<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1mbuxbpb"/><path class="qz_ogibcp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-map-pin-corner-duocolor" /></template>
<style>
.a1mbuxbpb {
  stroke-opacity: 0.4;
  d: path("M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qz_ogibcp {
  d: path("M17 10h-4.25a1 1 0 0 1-1-1V4a.35.35 0 0 0-.623-.217l-7.504 9.434A.482.482 0 0 0 4 14h3.25a1 1 0 0 1 1 1v5c0 .33.417.476.623.217l1.565-1.967");
}

</style>
