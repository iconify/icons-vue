<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zc9yrzbrg"/><path class="ihhy5kb9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-high-duocolor-round" /></template>
<style>
.ihhy5kb9w {
  d: path("M11 7v10c0 1.107-1.262 1.738-2 1l-1-1c-.64-.64-1.36-1-2-1H5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2h1c.64 0 1.36-.36 2-1l1-1c.738-.738 2-.107 2 1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zc9yrzbrg {
  stroke-opacity: 0.4;
  d: path("M15 8a7.21 7.21 0 0 1 0 8m3-11a11.4 11.4 0 0 1 0 14");
}

</style>
