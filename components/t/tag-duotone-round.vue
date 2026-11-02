<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fgrwmfblw"/><path class="aibye2byp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-duotone-round" /></template>
<style>
.aibye2byp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4h2c1.28 0 2.36.36 3 1l4 4a4.243 4.243 0 0 1 0 6l-2 2a4.243 4.243 0 0 1-6 0l-4-4c-.64-.64-1-1.72-1-3V8a4 4 0 0 1 4-4m0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.fgrwmfblw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4c1.041 0 2.236.237 3 1l4 4a4.24 4.24 0 0 1 0 6l-2 2a4.24 4.24 0 0 1-6 0l-4-4c-.763-.764-1-1.959-1-3V8a4 4 0 0 1 4-4Zm-1 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.ft5dv1b6b {
  fill: none;
}

</style>
