<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pxvo1zbqd"/><path class="hzocg_wak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-side-duocolor" /></template>
<style>
.hzocg_wak {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 7V5h3v2M9 7h3M5 4h1m9 0h1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pxvo1zbqd {
  stroke-opacity: 0.4;
  d: path("M5 18a2 2 0 0 1-2-2v-4l4-4c.64-.64 1.36-1 2-1h3c.64 0 1.36.36 2 1l4 4h1a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2M9 18h6M3 12h15m-8-5v5");
}

</style>
