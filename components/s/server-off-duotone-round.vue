<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ae1xzma9k"/><path class="rj14iwhba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-duotone-round" /></template>
<style>
.ae1xzma9k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 4h8a3 3 0 1 1 0 6h-2Zm-4 6a3 3 0 0 1-1.562-5.562L10 10Zm12 10H6a3 3 0 1 1 0-6h8l5.562 5.562A3 3 0 0 1 18 20");
}

.ft5dv1b6b {
  fill: none;
}

.rj14iwhba {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10H6a3 3 0 0 1-1.562-5.562M10 4h8a3 3 0 0 1 0 6h-2m3.562 9.562c-.455.278-.99.438-1.562.438H6a3 3 0 0 1 0-6h8m-7 3h.01M2 2l20 20");
}

</style>
