<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f89gwcbvk"/><path class="h0yj-4byq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-heart-corner-duotone-round" /></template>
<style>
.f89gwcbvk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.982 9.5a7.502 7.502 0 0 0-7.405 8.572L10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5M17 16c1-2 4-2 4 0s-4 4-4 4s-4-2-4-4s3-2 4 0");
}

.ft5dv1b6b {
  fill: none;
}

.h0yj-4byq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5M8 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m9 7c-1-2-4-2-4 0s4 4 4 4s4-2 4-4s-3-2-4 0");
}

</style>
