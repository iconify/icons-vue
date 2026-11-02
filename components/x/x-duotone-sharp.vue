<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mms4_pbmy"/><path class="mxyt-qc_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:x-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mms4_pbmy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 3a1 1 0 0 1 .8.4l12 16A.999.999 0 0 1 20 21h-4a1 1 0 0 1-.8-.4l-12-16A.999.999 0 0 1 4 3Z");
}

.mxyt-qc_z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m4 20l6-8m4 0l6-8M4 4h4l12 16h-4Z");
}

</style>
