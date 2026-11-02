<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vd5e6cbev"/><path class="sb7_1gy2u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-sparkle-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sb7_1gy2u {
  d: path("M7 5v7a2 2 0 1 0 4 0V5a2 2 0 1 0-4 0m2 13v3m-6-9a6 6 0 1 0 12 0");
}

.vd5e6cbev {
  stroke-opacity: 0.4;
  d: path("M18 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

</style>
