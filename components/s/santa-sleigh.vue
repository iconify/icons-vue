<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j1d78nbec"/><path class="mtz6t0baj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:santa-sleigh" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1d78nbec {
  d: path("M2.75 7.25A1.25 1.25 0 0 1 4 6h1a1.25 1.25 0 0 1 1.25 1.25v4h8c1.25 0 2-.75 2.5-2l.5-1.25A2 2 0 0 1 21 9.25c-.5 4-3 6.5-6.5 6.5H5a2.25 2.25 0 0 1-2.25-2.25Z");
}

.mtz6t0baj {
  d: path("M10.25 11.25h2a1 1 0 0 0 1-1c0-1.4-.75-2.3-1.5-2.75l.5-1.25h-2l.5 1.25c-.75.45-1.5 1.35-1.5 2.75a1 1 0 0 0 1 1M6.75 16v4.25M14 16v4.25m-11.25 0h14.5A3.75 3.75 0 0 0 21 16.5");
}

</style>
