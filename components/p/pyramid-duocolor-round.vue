<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i5w95gbde"/><path class="f81dtcb7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pyramid-duocolor-round" /></template>
<style>
.f81dtcb7o {
  d: path("m12 5l8.89 13.336A1.07 1.07 0 0 1 20 20H4a1.07 1.07 0 0 1-.89-1.664z");
}

.i5w95gbde {
  stroke-opacity: 0.4;
  d: path("m12 5l4 15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
