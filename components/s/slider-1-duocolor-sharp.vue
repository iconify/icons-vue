<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s8jfh9brl"/><path class="v19aulbzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-1-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s8jfh9brl {
  stroke-opacity: 0.4;
  d: path("M3 9h11m4 0h3M3 15h3m4 0h11");
}

.v19aulbzd {
  d: path("M14 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-8 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
