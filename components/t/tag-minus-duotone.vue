<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xlmsyp8zv"/><path class="qgkd4bziw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-minus-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qgkd4bziw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 14v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7l4-4h6l4 4zm-8-8h2m-4 8h6");
}

.xlmsyp8zv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 14v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7l4-4h6l4 4Z");
}

</style>
