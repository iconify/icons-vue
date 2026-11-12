<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h0mtk4f-s"/><path class="ynnynt80w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:regex-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h0mtk4f-s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 19a2 2 0 1 1 3.999-.001A2 2 0 0 1 3 19");
}

.ynnynt80w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 3v10m-4-8l8 6m-8 0l8-6M3 19a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
