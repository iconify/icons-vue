<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vbbz86bxc"/><path class="i2-1-fp0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-1-duocolor-round" /></template>
<style>
.i2-1-fp0k {
  d: path("M9 14a2 2 0 1 1 0 4a2 2 0 0 1 0-4m6-8a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vbbz86bxc {
  stroke-opacity: 0.4;
  d: path("M9 3v11m0 4v3m6-18v3m0 4v11");
}

</style>
