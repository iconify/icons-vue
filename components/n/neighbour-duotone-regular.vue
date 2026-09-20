<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qdlh6lbap"/><path class="ao9hey9_y"/><path class="jeaqztjrg"/><path class="pxkh6-9_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:neighbour-duotone-regular" /></template>
<style>
.ao9hey9_y {
  fill: currentColor;
  d: path("M14 18v-6l4 -4 4 4v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jeaqztjrg {
  d: path("M2 18v-6l4 -4 4 4v6Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pxkh6-9_k {
  d: path("M14 18v-6l4 -4 4 4v6Z");
}

.qdlh6lbap {
  fill: currentColor;
  d: path("M2 18v-6l4 -4 4 4v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
