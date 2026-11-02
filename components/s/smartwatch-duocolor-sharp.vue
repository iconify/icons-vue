<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="onadeachb"/><path class="ekxv2q3-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:smartwatch-duocolor-sharp" /></template>
<style>
.ekxv2q3-d {
  d: path("M6 6h12v12H6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.onadeachb {
  stroke-opacity: 0.4;
  d: path("M9 6V3h6v3M9 18v3h6v-3");
}

</style>
