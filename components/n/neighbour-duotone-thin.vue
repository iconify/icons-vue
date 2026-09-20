<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qdlh6lbap"/><path class="ao9hey9_y"/><path class="jeaqztjrg"/><path class="pxkh6-9_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:neighbour-duotone-thin" /></template>
<style>
.ao9hey9_y {
  fill: currentColor;
  d: path("M14 18v-6l4 -4 4 4v6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jeaqztjrg {
  d: path("M2 18v-6l4 -4 4 4v6Z");
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
