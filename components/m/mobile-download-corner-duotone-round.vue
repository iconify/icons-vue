<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a_rv6p-kh"/><path class="e7utdls-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-download-corner-duotone-round" /></template>
<style>
.a_rv6p-kh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 21a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v3a1 1 0 0 1-1 1a2 2 0 0 0-2 2Z");
}

.e7utdls-x {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v3m-3 11H7a4 4 0 0 1-4-4v-5m11 6l3 3l3-3m-3 3v-8");
}

.ft5dv1b6b {
  fill: none;
}

</style>
