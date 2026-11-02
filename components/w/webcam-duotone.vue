<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="k4x0zwmdz"/><path class="m7-y_v0cd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:webcam-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k4x0zwmdz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m6 0a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10m1 0a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.m7-y_v0cd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m4 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3 7v4m-4 0h8");
}

</style>
