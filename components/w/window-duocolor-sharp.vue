<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="adiypubxg"/><path class="e9jl5nxyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-duocolor-sharp" /></template>
<style>
.adiypubxg {
  stroke-opacity: 0.4;
  d: path("M3 8h18");
}

.e9jl5nxyo {
  d: path("M3 8V4h18v16H3z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
