<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rgz1udbfy"/><path class="vnp-17bas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rgz1udbfy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 16a2.003 2.003 0 0 1-2 2H7a4 4 0 0 1-4-4V8a2.003 2.003 0 0 1 2-2Zm0-6l-4-4a4 4 0 0 1 4 4m0 0l2-1c1.838-.919 4 .162 4 2v2c0 .791-.426 1.493-1.09 1.91Z");
}

.vnp-17bas {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.647 15.647A4 4 0 0 1 11 18H7a4 4 0 0 1-4-4v-4a4 4 0 0 1 2.354-3.646M11 6a4 4 0 0 1 4 4m0 0l2-1c1.838-.919 4 .162 4 2v2c0 .828-.44 1.503-1.09 1.91M2 3l19 19");
}

</style>
