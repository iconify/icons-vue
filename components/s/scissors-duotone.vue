<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="u5l3pwbfr"/><path class="ebajzhbrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scissors-duotone" /></template>
<style>
.ebajzhbrq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.121 15.879L21 3M8.121 8.121L12 12m3 3l6 6M3 6a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.u5l3pwbfr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 9a3 3 0 1 1 0-6a3 3 0 0 1 0 6m0 12a3 3 0 1 1 0-6a3 3 0 0 1 0 6");
}

</style>
