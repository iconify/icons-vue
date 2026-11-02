<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x-d5t_gmw"/><path class="g51bjacqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:truck-fast-duocolor-sharp" /></template>
<style>
.g51bjacqe {
  d: path("M5 18H3v-1M3 5h10v13m0-10h4l4 4v6h-2M9 18h6m-2-6h7M3 9h6m-6 4h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x-d5t_gmw {
  stroke-opacity: 0.4;
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
