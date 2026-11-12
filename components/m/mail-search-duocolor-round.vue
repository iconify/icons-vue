<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z6y07wbqv"/><path class="ofhcktb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ofhcktb3w {
  d: path("M21 14v1a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h3M4 7l3 3c.64.64 1.72 1 3 1h2");
}

.z6y07wbqv {
  stroke-opacity: 0.4;
  d: path("M14 4a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4m4 4l3 3");
}

</style>
