<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dhgerfbuh"/><path class="y0cq7_bhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:router-duotone-round" /></template>
<style>
.dhgerfbuh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 14h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8");
}

.ft5dv1b6b {
  fill: none;
}

.y0cq7_bhl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m4 0h.01M11 18h.01M16 12v3m-2-6a2.83 2.83 0 0 1 4 0m-7-3a7.07 7.07 0 0 1 10 0");
}

</style>
