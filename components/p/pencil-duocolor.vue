<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-h6ynb5v"/><path class="epqz_mzvk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-duocolor" /></template>
<style>
.epqz_mzvk {
  d: path("M4 16L15 5a1.414 1.414 0 0 1 2 0l2 2a1.414 1.414 0 0 1 0 2L8 20m4-12l4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-h6ynb5v {
  stroke-opacity: 0.4;
  d: path("M8 20H4v-4");
}

</style>
