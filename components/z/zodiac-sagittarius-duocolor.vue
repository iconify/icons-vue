<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvopqdb9p"/><path class="u0zn-1eit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-sagittarius-duocolor" /></template>
<style>
.jvopqdb9p {
  stroke-opacity: 0.4;
  d: path("M14 3h7v7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0zn-1eit {
  d: path("M3 21L21 3M6 12l6 6");
}

</style>
