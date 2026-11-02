<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xzvom3b5z"/><path class="k47t5rb9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-duocolor-round" /></template>
<style>
.k47t5rb9n {
  d: path("M3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M10 3h4m7 7v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xzvom3b5z {
  stroke-opacity: 0.4;
  d: path("M3 14a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Z");
}

</style>
