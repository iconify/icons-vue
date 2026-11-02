<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tjyn6ac5s"/><path class="bhjf0ktnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microphone-duocolor-round" /></template>
<style>
.bhjf0ktnt {
  d: path("M9 6v5a3 3 0 0 0 6 0V6a3 3 0 0 0-6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tjyn6ac5s {
  stroke-opacity: 0.4;
  d: path("M12 18v3M5 10v1a7 7 0 0 0 14 0v-1");
}

</style>
