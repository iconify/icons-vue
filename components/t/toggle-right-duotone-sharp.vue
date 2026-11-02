<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ur22bq0yu"/><path class="dck4vac8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-right-duotone-sharp" /></template>
<style>
.dck4vac8t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 12a6 6 0 0 1 6-6h6a6 6 0 1 1 0 12H9a6 6 0 0 1-6-6m9 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.ur22bq0yu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 6h6a6 6 0 1 1 0 12H9A6 6 0 1 1 9 6m6 9a3 3 0 1 0 0-6a3 3 0 0 0 0 6");
}

</style>
