<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b259x8beh"/><path class="w-5mz7bdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-leo-duocolor-round" /></template>
<style>
.b259x8beh {
  stroke-opacity: 0.4;
  d: path("M13 17a4 4 0 1 0 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-5mz7bdz {
  d: path("M9 16a3 3 0 1 0-6 0a3 3 0 0 0 6 0c0-4-2-6-2-9a4 4 0 1 1 8 0c0 4-2 6-2 10");
}

</style>
