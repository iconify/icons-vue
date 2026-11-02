<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tom0rnb2s"/><path class="bqycojb_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-duocolor-round" /></template>
<style>
.bqycojb_m {
  d: path("M18 3a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3m18-8v4m-7 7h-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tom0rnb2s {
  stroke-opacity: 0.4;
  d: path("M3 7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
