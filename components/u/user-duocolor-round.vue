<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ja-dv5mey"/><path class="nk9dftb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-duocolor-round" /></template>
<style>
.ja-dv5mey {
  stroke-opacity: 0.4;
  d: path("M6 21a6 6 0 1 1 12 0");
}

.nk9dftb5b {
  d: path("M8 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
