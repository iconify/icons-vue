<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vnl89fbsd"/><path class="h4f8xqbrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:page-margins-duocolor-sharp" /></template>
<style>
.h4f8xqbrj {
  d: path("M5 3h14v18H5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vnl89fbsd {
  stroke-opacity: 0.4;
  d: path("M9 7h6v10H9Z");
}

</style>
