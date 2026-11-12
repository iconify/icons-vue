<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y3i0hurhy"/><path class="rl8l5xxgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-into-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.rl8l5xxgq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3v10m-3-3l3 3l3-3m-5 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.y3i0hurhy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 19a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 19");
}

</style>
