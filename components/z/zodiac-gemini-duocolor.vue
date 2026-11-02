<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cij2gvuxr"/><path class="u3zzgdblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-gemini-duocolor" /></template>
<style>
.cij2gvuxr {
  stroke-opacity: 0.4;
  d: path("M7 5v14M17 5v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u3zzgdblm {
  d: path("M3 3a15.81 15.81 0 0 0 18 0M3 21a15.81 15.81 0 0 1 18 0");
}

</style>
