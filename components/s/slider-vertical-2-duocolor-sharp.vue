<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8zkm23pf"/><path class="wrsjigb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-2-duocolor-sharp" /></template>
<style>
.c8zkm23pf {
  stroke-opacity: 0.4;
  d: path("M6 3v5m0 4v9m6-18v11m0 4v3m6-18v3m0 4v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wrsjigb-f {
  d: path("M6 8a2 2 0 1 1 0 4a2 2 0 0 1 0-4m6 6a2 2 0 1 1 0 4a2 2 0 0 1 0-4m6-8a2 2 0 1 1 0 4a2 2 0 0 1 0-4");
}

</style>
