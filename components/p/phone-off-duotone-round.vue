<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g3oennpau"/><path class="wi20y6f7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g3oennpau {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 2h1c2.253 0 4.118 1.603 4.928 3.629c.351.877.592 1.812.592 2.761c0 .419-.05.84-.177 1.24a2.65 2.65 0 0 1-.636 1.077a1.123 1.123 0 0 0 0 1.586l2 2a1.123 1.123 0 0 0 1.586 0c.459-.459 1.038-.777 1.651-.982A6.5 6.5 0 0 1 18 13h1c.53 0 1.023.211 1.424.551C21.61 14.555 22 16.522 22 18v1c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 22a16.8 16.8 0 0 1-6.617-1.336a16.9 16.9 0 0 1-5.404-3.643a16.9 16.9 0 0 1-3.643-5.404A16.8 16.8 0 0 1 2 5c0-.797.314-1.558.879-2.121A3 3 0 0 1 5 2");
}

.wi20y6f7d {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 16C5.105 13.105 3 9.418 3 5a2 2 0 0 1 2-2h1c1.691 0 3.275 1.188 4 3c.693 1.733.693 3.307 0 4a2.12 2.12 0 0 0 0 3v1m5 1c.64-.64 1.72-1 3-1h1c1.105 0 2 1.79 2 4v1a2 2 0 0 1-2 2c-2.878 0-5.667-.67-8-2m-9 3L22 2");
}

</style>
