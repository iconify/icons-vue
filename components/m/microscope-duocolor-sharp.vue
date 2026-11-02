<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t0kd1md4b"/><path class="t2hdo3h8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:microscope-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t0kd1md4b {
  stroke-opacity: 0.4;
  d: path("M14 21a6 6 0 0 0 6-6a5 5 0 0 0-5-5h-2");
}

.t2hdo3h8p {
  d: path("M7 6h6v7H7zm1 0V3h4v3M3 21h18M6 17h8");
}

</style>
