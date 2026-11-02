<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vfecxbbca"/><path class="by4l_9bgq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trophy-duocolor-sharp" /></template>
<style>
.by4l_9bgq {
  d: path("M7 9V3h10v6A5 5 0 0 1 7 9m3 5v2c0 2-3 2-3 5m7-7v2c0 2 3 2 3 5M6 21h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vfecxbbca {
  stroke-opacity: 0.4;
  d: path("M7 5H5a2 2 0 1 0 0 4h2m10-4h2a2 2 0 1 1 0 4h-2");
}

</style>
