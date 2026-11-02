<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wglsxvt_i"/><path class="gt5p92bmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-track-duocolor" /></template>
<style>
.gt5p92bmk {
  d: path("M3 17L17 3M7 21L21 7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wglsxvt_i {
  stroke-opacity: 0.4;
  d: path("m3 13l2 2m0 0l4 4m0 0l2 2M8 8l2 2m0 0l4 4m0 0l2 2M13 3l2 2m0 0l4 4m0 0l2 2");
}

</style>
