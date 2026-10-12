<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="y-fd6pbmc"/><path class="gvt49nbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:retrieval-search" /></template>
<style>
.gvt49nbqv {
  d: path("M15.6 15.6L21 21M10.25 6.25q.48 3.52 4 4q-3.52.48-4 4q-.48-3.52-4-4q3.52-.48 4-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y-fd6pbmc {
  cx: 10.25px;
  cy: 10.25px;
  r: 7.5px;
}

</style>
