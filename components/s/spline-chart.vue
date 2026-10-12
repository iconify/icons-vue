<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ux32n0bfz"/><path class="aw3plfa_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spline-chart" /></template>
<style>
.aw3plfa_h {
  d: path("M7 16.25c3 0 2.75-8.5 6-8.5s2.75 5 5 5c1 0 1.5-1.5 2.25-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux32n0bfz {
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5");
}

</style>
