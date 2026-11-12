<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="luej32qfe"/><path class="elfn6foso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-arrow-down-duocolor-round" /></template>
<style>
.elfn6foso {
  d: path("M3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3m7-15h4m7 7v4m-7 7h-4m-7-7v-4");
}

.luej32qfe {
  stroke-opacity: 0.4;
  d: path("m9 13l3 3l3-3m-3 3V8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
