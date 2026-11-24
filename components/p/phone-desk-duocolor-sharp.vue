<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j7mttacph"/><path class="gvvj0-gua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:phone-desk-duocolor-sharp" /></template>
<style>
.gvvj0-gua {
  d: path("M15 5H3v14h12M6 9h6m-6 4h.01M9 13h.01M12 13h.01M6 16h.01M9 16h.01M12 16h.01");
}

.j7mttacph {
  stroke-opacity: 0.4;
  d: path("M15 3h6v18h-6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
