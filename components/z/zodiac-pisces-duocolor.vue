<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gtmr7ugch"/><path class="qts689b8w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-pisces-duocolor" /></template>
<style>
.gtmr7ugch {
  stroke-opacity: 0.4;
  d: path("M5 12h2m0 0h10m0 0h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qts689b8w {
  d: path("M4 3a15 15 0 0 1 0 18M20 3a15 15 0 0 0 0 18");
}

</style>
