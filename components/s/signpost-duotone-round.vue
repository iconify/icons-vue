<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fc17-jbir"/><path class="kkhz1abus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-duotone-round" /></template>
<style>
.fc17-jbir {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 6c1.041 0 2.236.237 3 1l1 1a1.415 1.415 0 0 1 0 2l-1 1c-.764.763-1.959 1-3 1H7a3 3 0 1 1 0-6Z");
}

.ft5dv1b6b {
  fill: none;
}

.kkhz1abus {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 6h5c1.28 0 2.36.36 3 1l1 1a1.414 1.414 0 0 1 0 2l-1 1c-.64.64-1.72 1-3 1H7a3 3 0 0 1 0-6zm2-3v3m0 6v9");
}

</style>
