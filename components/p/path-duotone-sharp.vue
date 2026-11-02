<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c856fpvcp"/><path class="mtkwm5czr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:path-duotone-sharp" /></template>
<style>
.c856fpvcp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 9a3 3 0 1 1 0-6a3 3 0 0 1 0 6M6 21a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

.ft5dv1b6b {
  fill: none;
}

.mtkwm5czr {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.121 15.879L15.88 8.12M3 18a3 3 0 1 0 6 0a3 3 0 0 0-6 0M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
