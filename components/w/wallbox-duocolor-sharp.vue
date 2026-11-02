<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z64abgesa"/><path class="tv11bsxyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallbox-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tv11bsxyz {
  d: path("M3 3h10v12H3Zm5 12v4h11v-6m-2-6h4v6h-4Z");
}

.z64abgesa {
  stroke-opacity: 0.4;
  d: path("M9 6L6 9h4l-3 3");
}

</style>
