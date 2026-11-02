<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jsdo7gbfr"/><path class="fqhdb8bsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:router-duocolor" /></template>
<style>
.fqhdb8bsv {
  d: path("M3 17a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm4 1h.01M11 18h.01");
}

.jsdo7gbfr {
  stroke-opacity: 0.4;
  d: path("M16 12v3m-2-6a2.83 2.83 0 0 1 4 0m-7-3a7.07 7.07 0 0 1 10 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
