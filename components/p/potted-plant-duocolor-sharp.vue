<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k8695sbsq"/><path class="j6128acsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:potted-plant-duocolor-sharp" /></template>
<style>
.j6128acsi {
  d: path("M7 16h10v5H7zm5 0V9");
}

.k8695sbsq {
  stroke-opacity: 0.4;
  d: path("M12 9a6 6 0 0 0-6-6H3v2a6 6 0 0 0 6 6h3Zm0 2a6 6 0 0 1 6-6h3v1a6 6 0 0 1-6 6h-3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
