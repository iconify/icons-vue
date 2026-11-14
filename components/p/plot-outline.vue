<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_a5jubhp"/><path class="p6q1ehbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plot-outline" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6q1ehbpa {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M7.25 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6.25-3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M10 16.25l3.75-2M8 7h2.75");
}

.w_a5jubhp {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5");
}

</style>
