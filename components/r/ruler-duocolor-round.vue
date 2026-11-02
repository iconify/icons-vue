<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eba0prbjj"/><path class="qmj5syb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ruler-duocolor-round" /></template>
<style>
.eba0prbjj {
  stroke-opacity: 0.4;
  d: path("m5 13l2 2m2-6l2 2m2-6l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qmj5syb0p {
  d: path("m9 9l4-4a2.83 2.83 0 0 1 4 0l2 2a2.83 2.83 0 0 1 0 4l-8 8a2.83 2.83 0 0 1-4 0l-2-2a2.83 2.83 0 0 1 0-4z");
}

</style>
