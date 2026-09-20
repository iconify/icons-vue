<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xb280sbwz"/><path class="ur9jjfbgq"/><path class="qoupp8b_p"/><path class="i5be34b7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:window-seat-duotone-regular" /></template>
<style>
.i5be34b7d {
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qoupp8b_p {
  d: path("M4 4v16h8V4Z");
}

.ur9jjfbgq {
  fill: currentColor;
  d: path("M13 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xb280sbwz {
  fill: currentColor;
  d: path("M4 4v16h8V4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
