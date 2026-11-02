<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cka-s8b3p"/><path class="he65uacuo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-duocolor-round" /></template>
<style>
.cka-s8b3p {
  stroke-opacity: 0.4;
  d: path("M10 7a4 4 0 0 1 4-4h3a4 4 0 0 1 4 4v3a4 4 0 0 1-4 4h-3a4 4 0 0 1-4-4Z");
}

.he65uacuo {
  d: path("M3 6a3 3 0 0 1 3-3m15 15a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3m11 3h-4m-7-7v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
