<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z6y07wbqv"/><path class="ll0wy-n4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-search-duocolor" /></template>
<style>
.ll0wy-n4j {
  d: path("M21 14v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h5M4 6l4 4c.64.64 1.36 1 2 1h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z6y07wbqv {
  stroke-opacity: 0.4;
  d: path("M14 4a2.828 2.828 0 1 1 4 4a2.828 2.828 0 0 1-4-4m4 4l3 3");
}

</style>
