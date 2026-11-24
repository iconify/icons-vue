<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fag8hwbgy"/><path class="ricnuhbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-record-duocolor-sharp" /></template>
<style>
.fag8hwbgy {
  stroke-opacity: 0.4;
  d: path("M15 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0m3 0h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ricnuhbyg {
  d: path("M3 5V3h6l2 5l-3 3l5 5l3-3l5 2v6h-2C10.163 21 3 13.837 3 5");
}

</style>
