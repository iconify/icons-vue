<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ipx4f3mqs"/><path class="p8oxtqbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:step-over-duocolor-sharp" /></template>
<style>
.ipx4f3mqs {
  stroke-opacity: 0.4;
  d: path("M16 19a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p8oxtqbzn {
  d: path("M4 11a7 7 0 0 1 14 0v2m-3-3l3 3l3-3");
}

</style>
