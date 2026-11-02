<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a4-x0obbu"/><path class="n95tp7ogp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-side-duocolor-round" /></template>
<style>
.a4-x0obbu {
  stroke-opacity: 0.4;
  d: path("M5 18a2 2 0 0 1-2-2v-4l4-4c.64-.64 1.72-1 3-1h1c1.28 0 2.36.36 3 1l4 4h1a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2M9 18h6M3 12h15m-8-5v5");
}

.n95tp7ogp {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0M9 4h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
