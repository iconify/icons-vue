<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x-d5t_gmw"/><path class="nsjv8-svv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suv-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nsjv8-svv {
  d: path("M5 18a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4h6l4 4h2a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2M9 18h6M3 10h14m-7-4v4");
}

.x-d5t_gmw {
  stroke-opacity: 0.4;
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
