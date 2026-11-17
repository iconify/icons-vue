<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u4s89eblc"/><path class="ie9su5bjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprinkler-duocolor" /></template>
<style>
.ie9su5bjz {
  d: path("M10 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v5m-4 0h8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4s89eblc {
  stroke-opacity: 0.4;
  d: path("M8 10h.01M12 8h.01M16 10h.01M5 7h.01M9 4h.01M15 4h.01M19 7h.01");
}

</style>
