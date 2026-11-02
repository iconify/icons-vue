<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a_rv6p-kh"/><path class="woao9qv_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-upload-corner-duotone-round" /></template>
<style>
.a_rv6p-kh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 21a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v3a1 1 0 0 1-1 1a2 2 0 0 0-2 2Z");
}

.ft5dv1b6b {
  fill: none;
}

.woao9qv_b {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12V7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v3m-3 11H7a4 4 0 0 1-4-4v-5m17 4l-3-3l-3 3m3-3v8");
}

</style>
