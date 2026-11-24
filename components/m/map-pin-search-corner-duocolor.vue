<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ok035ubks"/><path class="ncrpcqudc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-search-corner-duocolor" /></template>
<style>
.ncrpcqudc {
  d: path("M10 21c-3-2-7-6-7-11a7 7 0 0 1 13.982-.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ok035ubks {
  stroke-opacity: 0.4;
  d: path("M8 9a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 9a2.828 2.828 0 1 1-4-4a2.828 2.828 0 0 1 4 4m0 0l3 3");
}

</style>
