<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m6k_1eoog"/><path class="f3t91bc-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shirt-duotone-sharp" /></template>
<style>
.f3t91bc-s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 4L3 6v5h3v9h12v-9h3V6l-6-2m0 0a3 3 0 0 1-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.m6k_1eoog {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.316 3.051l6 2A1 1 0 0 1 22 6v5a1 1 0 0 1-1 1h-2v8a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-8H3a1 1 0 0 1-1-1V6a1 1 0 0 1 .684-.949l6-2A1.002 1.002 0 0 1 10 4a2 2 0 1 0 4 0a1 1 0 0 1 1.316-.949");
}

</style>
