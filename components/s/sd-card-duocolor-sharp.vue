<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kggl7bbex"/><path class="zmrygkbut"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sd-card-duocolor-sharp" /></template>
<style>
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

.zmrygkbut {
  d: path("m5 7l4-4h10v18H5z");
}

</style>
