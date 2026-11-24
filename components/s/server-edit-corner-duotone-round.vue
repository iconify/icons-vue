<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gml5-mb-g"/><path class="o-93e7gnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-edit-corner-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gml5-mb-g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 4h12a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6m7 17v-3l5-5l3 3l-5 5Zm-4-1H6a3 3 0 1 1 0-6h3Z");
}

.o-93e7gnn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 7a3 3 0 0 1 3-3h12a3 3 0 0 1 0 6H6a3 3 0 0 1-3-3m6 13H6a3 3 0 0 1 0-6h3M7 7h.01M7 17h.01M13 21v-3l5-5l3 3l-5 5Z");
}

</style>
