<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q71vj5lnb"/><path class="fiup64xoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:router-duotone-sharp" /></template>
<style>
.fiup64xoc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15h18v6H3Zm4 3h.01M11 18h.01M16 12v3m-2-6a2.83 2.83 0 0 1 4 0m-7-3a7.07 7.07 0 0 1 10 0");
}

.ft5dv1b6b {
  fill: none;
}

.q71vj5lnb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 21v-6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
