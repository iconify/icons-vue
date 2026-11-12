<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vpw7ljb-v"/><path class="ly44l6qmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-search-duocolor-round" /></template>
<style>
.ly44l6qmn {
  d: path("M3 7a4 4 0 0 1 4-4m10 0a4 4 0 0 1 4 4m0 10a4 4 0 0 1-4 4M7 21a4 4 0 0 1-4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vpw7ljb-v {
  stroke-opacity: 0.4;
  d: path("M8 8a4.243 4.243 0 1 1 6 6a4.243 4.243 0 0 1-6-6m6 6l3 3");
}

</style>
