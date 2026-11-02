<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zv4_8jbnl"/><path class="g-yrhccyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-sparkle-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g-yrhccyj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v18H3Zm9 4c0 3 2 5 5 5c-3 0-5 2-5 5c0-3-2-5-5-5c3 0 5-2 5-5");
}

.zv4_8jbnl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 3v18H3V3Z");
}

</style>
