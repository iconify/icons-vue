<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q3dpwpbvj"/><path class="crq9tybqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:x-duocolor-round" /></template>
<style>
.crq9tybqe {
  d: path("m4 20l6-8m4 0l6-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q3dpwpbvj {
  stroke-opacity: 0.4;
  d: path("M4 4h4l12 16h-4Z");
}

</style>
