<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g1ti6243i"/><path class="uepdcyzyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soup-duocolor-round" /></template>
<style>
.g1ti6243i {
  stroke-opacity: 0.4;
  d: path("M9 5L8 7m5-2l-1 2m5-2l-1 2m3 4l2-5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uepdcyzyv {
  d: path("M3 11h18a9 9 0 0 1-18 0");
}

</style>
