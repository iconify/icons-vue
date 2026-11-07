<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="voeieob5r"/><path class="h7i2w8b6i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-duocolor-round" /></template>
<style>
.h7i2w8b6i {
  d: path("M6 16v-5a4 4 0 0 1 4-4h5m3 3v3a4 4 0 0 1-4 4h-3m1 0v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.voeieob5r {
  stroke-opacity: 0.4;
  d: path("M9 3v4m6-4v4M2 20L20 2");
}

</style>
