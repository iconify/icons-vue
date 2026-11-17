<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="faqpx9bxk"/><path class="byr2wcn0d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-zap-duocolor-sharp" /></template>
<style>
.byr2wcn0d {
  d: path("m12 2l10 18H2Z");
}

.faqpx9bxk {
  stroke-opacity: 0.4;
  d: path("m13 11l-3 3h4l-3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
