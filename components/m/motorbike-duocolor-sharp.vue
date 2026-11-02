<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b544gtb_t"/><path class="v92bd3bjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:motorbike-duocolor-sharp" /></template>
<style>
.b544gtb_t {
  stroke-opacity: 0.4;
  d: path("m3 10l6 2a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v92bd3bjo {
  d: path("M3 18a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0m12 0a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0m-6 0h2a1 1 0 0 0 1-1a5 5 0 0 1 5-5a1 1 0 0 0 1-1m0 4V8a2 2 0 0 0-2-2");
}

</style>
