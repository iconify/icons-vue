<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p1evxrbfr"/><path class="e0y42mbja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-duocolor-round" /></template>
<style>
.e0y42mbja {
  d: path("M5 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p1evxrbfr {
  stroke-opacity: 0.4;
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3 7v4m-4 0h8");
}

</style>
