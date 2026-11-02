<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ajs1cvb5o"/><path class="ef1bkfb-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-voice-duotone-sharp" /></template>
<style>
.ajs1cvb5o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.393 5.053a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M15 22H3a1 1 0 0 1-1-1a6.9 6.9 0 0 1 .551-2.725A6.9 6.9 0 0 1 4.05 16.05A6.97 6.97 0 0 1 9 14c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-1 1");
}

.ef1bkfb-s {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 1 1 12 0m2-17a6.7 6.7 0 0 1 0 6m3-7a9.85 9.85 0 0 1 0 8");
}

.ft5dv1b6b {
  fill: none;
}

</style>
