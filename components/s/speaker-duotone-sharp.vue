<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ml0-q55cy"/><path class="rcr3d6bfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:speaker-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ml0-q55cy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 3v18H5V3Zm-7 14a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

.rcr3d6bfv {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 3h14v18H5Zm7 4h.01M9 14a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
