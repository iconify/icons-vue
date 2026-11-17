<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xljesbcwb"/><path class="ye-xh68uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-edit-corner-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.xljesbcwb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 11a4 4 0 1 1 0-8a4 4 0 0 1 0 8m4 10v-3l5-5l3 3l-5 5Zm-4-6v6H3a6 6 0 0 1 6-6");
}

.ye-xh68uz {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a4 4 0 1 0 8 0a4 4 0 0 0-8 0M3 21a6 6 0 0 1 6-6m4 6v-3l5-5l3 3l-5 5Z");
}

</style>
