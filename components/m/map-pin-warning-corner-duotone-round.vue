<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="l1h_dlbmq"/><path class="m-1uvhbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-warning-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l1h_dlbmq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5a7.502 7.502 0 0 0-7.405 8.572Z");
}

.m-1uvhbgj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5M8 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9 5v4m0 3h.01");
}

</style>
