<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ipwdx3bty"/><path class="e6grhjbhw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scroll-duocolor-sharp" /></template>
<style>
.e6grhjbhw {
  d: path("M18 17V3H5m2 2v14");
}

.ipwdx3bty {
  stroke-opacity: 0.4;
  d: path("M7 5a2 2 0 1 0-4 0v2a1 1 0 0 0 1 1h3m0 11a2 2 0 1 0 4 0v-1a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v1a2 2 0 0 1-2 2H9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
