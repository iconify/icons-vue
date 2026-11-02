<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kmyrh0g7g"/><path class="ncxbaeb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-duocolor" /></template>
<style>
.kmyrh0g7g {
  stroke-opacity: 0.4;
  d: path("M10 5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2Z");
}

.ncxbaeb4g {
  d: path("M3 6V5a2 2 0 0 1 2-2h1m15 15v1a2 2 0 0 1-2 2h-1M6 21H5a2 2 0 0 1-2-2v-1m11 3h-4m-7-7v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
