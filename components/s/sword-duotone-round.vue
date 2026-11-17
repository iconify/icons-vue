<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tv8li4bwl"/><path class="dg6f8u7wi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-duotone-round" /></template>
<style>
.dg6f8u7wi {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14L17 4c.64-.64 1.72-1 3-1h1v1c0 1.28-.36 2.36-1 3L10 17m-5-5l7 7m-4-3l-4 4m-1-1l2 2");
}

.ft5dv1b6b {
  fill: none;
}

.tv8li4bwl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 14L17 4c.764-.763 1.959-1 3-1h1v1c0 1.041-.237 2.236-1 3L10 17Z");
}

</style>
