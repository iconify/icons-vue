<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eu5ifdchi"/><path class="d0cosab-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sensor-duocolor" /></template>
<style>
.d0cosab-p {
  d: path("M3 13a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm5-2v10m-5-5h10");
}

.eu5ifdchi {
  stroke-opacity: 0.4;
  d: path("M17 11a4 4 0 0 0-4-4m8 4a8 8 0 0 0-8-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
