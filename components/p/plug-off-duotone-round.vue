<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="sbjs6qbal"/><path class="p-88rzyrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.p-88rzyrq {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 16v-5a4 4 0 0 1 4-4h5m3 3v3a4 4 0 0 1-4 4h-3m1 0v4M9 3v4m6-4v4M2 20L20 2");
}

.sbjs6qbal {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6.716 15.284A3.97 3.97 0 0 1 6 13v-2a4 4 0 0 1 4-4h4q.455 0 .899.101Zm11.183-5.183q.1.444.101.899v2a4 4 0 0 1-4 4h-3Z");
}

</style>
