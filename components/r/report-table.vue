<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="sqw3feb_h"/><path class="xdsqwhb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:report-table" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sqw3feb_h {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M9.25 9h5.5a1.75 1.75 0 0 1 1.75 1.75v6.5A1.75 1.75 0 0 1 14.75 19h-5.5a1.75 1.75 0 0 1-1.75-1.75v-6.5A1.75 1.75 0 0 1 9.25 9M7.5 12h9m-5.75-3v7");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

.xdsqwhb3l {
  fill: currentColor;
  d: path("M9 16h6a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 15 19H9a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 9 16");
}

</style>
