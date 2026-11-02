<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c8sd11-rw"/><path class="h-qgycbog"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-duotone-round" /></template>
<style>
.c8sd11-rw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 10a4 4 0 0 1 4-4h6a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4Z");
}

.ft5dv1b6b {
  fill: none;
}

.h-qgycbog {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14v2a4 4 0 0 1-4 4H9a4 4 0 0 1-4-4V9a3 3 0 0 1 3-3m4 0h3a4 4 0 0 1 4 4m-4-7l-3 3l3 3");
}

</style>
