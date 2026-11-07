<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j47yg1kmm"/><path class="w9a6t4fsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-upload-duocolor-round" /></template>
<style>
.j47yg1kmm {
  stroke-opacity: 0.4;
  d: path("m15 10l-3-3l-3 3m3-3v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w9a6t4fsv {
  d: path("M4 8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4v5a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm5 12h6");
}

</style>
