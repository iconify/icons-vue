<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dpsf-bb7q"/><path class="v4-7nlbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-search-duocolor-round" /></template>
<style>
.dpsf-bb7q {
  stroke-opacity: 0.4;
  d: path("M9 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m4 2l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v4-7nlbro {
  d: path("M5 6c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V8zM4 8h16");
}

</style>
