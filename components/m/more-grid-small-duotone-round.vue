<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bgqjtbbtc"/><path class="o3dm7ibqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-grid-small-duotone-round" /></template>
<style>
.bgqjtbbtc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 10a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-6 6a1 1 0 1 1 0-2a1 1 0 0 1 0 2m6 0a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.o3dm7ibqc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 9a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-6 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
