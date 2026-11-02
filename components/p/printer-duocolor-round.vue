<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d5tjzhk8f"/><path class="xjhs-wb7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:printer-duocolor-round" /></template>
<style>
.d5tjzhk8f {
  stroke-opacity: 0.4;
  d: path("M6 18a3 3 0 0 1 3-3h6a3 3 0 0 1 0 6H9a3 3 0 0 1-3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xjhs-wb7m {
  d: path("M6 17a3 3 0 0 1-3-3v-3a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4v3a3 3 0 0 1-3 3M6 7a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4m-8 4h4");
}

</style>
