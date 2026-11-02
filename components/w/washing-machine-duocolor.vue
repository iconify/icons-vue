<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="couc1ac6n"/><path class="yvkga2f9j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:washing-machine-duocolor" /></template>
<style>
.couc1ac6n {
  stroke-opacity: 0.4;
  d: path("M9 15a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yvkga2f9j {
  d: path("M4 5a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm0 4h16M8 6h.01M11 6h.01");
}

</style>
