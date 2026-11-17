<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w1te0zbhr"/><path class="pjgpcwb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:security-camera-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pjgpcwb8s {
  d: path("M3.755 9.139a2 2 0 0 1 1.414-2.45L16.76 3.583a2 2 0 0 1 2.45 1.415l1.035 3.863a2 2 0 0 1-1.414 2.45L7.24 14.417a2 2 0 0 1-2.45-1.415ZM12 13.14V17h7m0-1v5");
}

.w1te0zbhr {
  stroke-opacity: 0.4;
  d: path("m15.605 6.999l.518 1.932");
}

</style>
