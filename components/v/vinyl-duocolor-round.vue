<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ixc70hbeb"/><path class="sql93pbpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vinyl-duocolor-round" /></template>
<style>
.ixc70hbeb {
  stroke-opacity: 0.4;
  d: path("M6 12a6 6 0 0 1 6-6m6 6a6 6 0 0 1-6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sql93pbpx {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0m7 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
