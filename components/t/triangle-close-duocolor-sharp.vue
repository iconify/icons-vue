<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pane80bkq"/><path class="byr2wcn0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-close-duocolor-sharp" /></template>
<style>
.byr2wcn0d {
  d: path("m12 2l10 18H2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pane80bkq {
  stroke-opacity: 0.4;
  d: path("m10 12l4 4m0-4l-4 4");
}

</style>
