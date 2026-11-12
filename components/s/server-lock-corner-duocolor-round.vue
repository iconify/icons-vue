<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o7b8nccnb"/><path class="z7y7a6b7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o7b8nccnb {
  stroke-opacity: 0.4;
  d: path("M13 18a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2Zm2-2v-1a2 2 0 1 1 4 0v1");
}

.z7y7a6b7p {
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m0 7h6m0 6H6a3 3 0 0 1-3-3v-3m4-7h.01M7 17h.01");
}

</style>
