<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u6thig5fy"/><path class="ue2_f7zks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-lock-corner-duocolor-sharp" /></template>
<style>
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

.ue2_f7zks {
  d: path("M3 8V4h18v4M8 20H3V8m0 0h18");
}

</style>
