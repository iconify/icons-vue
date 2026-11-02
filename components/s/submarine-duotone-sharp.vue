<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fe1xl4brb"/><path class="e_c2htykb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-duotone-sharp" /></template>
<style>
.e_c2htykb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 20H7v-8h3V8h4v4h3a4 4 0 1 1 0 8M3 12v8m0-4h4m5-8V4h4m-4 12h.01M16 16h.01");
}

.fe1xl4brb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 21a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1h2V8a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3h2a5 5 0 0 1 0 10Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
