<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u6thig5fy"/><path class="n0uo4wbqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-duocolor-sharp" /></template>
<style>
.n0uo4wbqj {
  d: path("M3 4h18v6H3Zm6 16H3v-6h6M7 7h.01M7 17h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u6thig5fy {
  stroke-opacity: 0.4;
  d: path("M13 16h8v5h-8Zm2 0v-1a2 2 0 1 1 4 0v1");
}

</style>
