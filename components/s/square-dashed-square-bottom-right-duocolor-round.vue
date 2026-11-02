<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fqbc1ypih"/><path class="sautgxbgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-bottom-right-duocolor-round" /></template>
<style>
.fqbc1ypih {
  stroke-opacity: 0.4;
  d: path("M10 14a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4h-3a4 4 0 0 1-4-4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sautgxbgs {
  d: path("M3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3M6 21a3 3 0 0 1-3-3m7-15h4M3 14v-4");
}

</style>
