<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="furh41jlz"/><path class="l6paavbvb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-warning-duocolor-round" /></template>
<style>
.furh41jlz {
  stroke-opacity: 0.4;
  d: path("M12 8v5m0 3h.01");
}

.l6paavbvb {
  d: path("M12 3h2c1.28 0 2.36.36 3 1l3 3c.64.64 1 1.72 1 3v4c0 1.28-.36 2.36-1 3l-3 3c-.64.64-1.72 1-3 1h-4c-1.28 0-2.36-.36-3-1l-3-3c-.64-.64-1-1.72-1-3v-4c0-1.28.36-2.36 1-3l3-3c.64-.64 1.72-1 3-1z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
