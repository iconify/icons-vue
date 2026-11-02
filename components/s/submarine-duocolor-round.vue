<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jn0wn40go"/><path class="nnw25ybeb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:submarine-duocolor-round" /></template>
<style>
.jn0wn40go {
  stroke-opacity: 0.4;
  d: path("M12 16h.01M16 16h.01");
}

.nnw25ybeb {
  d: path("M17 20h-7a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3V9a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h3a4 4 0 1 1 0 8M3 12v8m0-4h4m5-8V6a2 2 0 0 1 2-2h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
