<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rp_vibb3t"/><path class="bot-r4bhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tram-duocolor-round" /></template>
<style>
.bot-r4bhg {
  d: path("M12 7h3a4 4 0 0 1 4 4v6a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2v-6a4 4 0 0 1 4-4zM8 19l-1 2m9-2l1 2M5 13h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rp_vibb3t {
  stroke-opacity: 0.4;
  d: path("M9 3h6m-3 0v4m-3 9h.01M15 16h.01");
}

</style>
