<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i8l66kykq"/><path class="u5smbtljw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i8l66kykq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 4l8 8l-8 8l-8-8V4Zm-3 6a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.u5smbtljw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 4h4l8 8l-8 8l-8-8V4zm0 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
