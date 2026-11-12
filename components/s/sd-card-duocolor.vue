<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kggl7bbex"/><path class="gws0fhb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-duocolor" /></template>
<style>
.gws0fhb9y {
  d: path("M19 12v7a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8c0-.64.36-1.36 1-2l2-2c.64-.64 1.36-1 2-1h7a2 2 0 0 1 2 2z");
}

.kggl7bbex {
  stroke-opacity: 0.4;
  d: path("M10 7v3m3-3v3m3-3v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
