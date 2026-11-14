<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="supb-eb6i"/><path class="x9o3dbc9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-joint" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.supb-eb6i {
  d: path("M2.5 10.5L12 3l9.5 7.5");
}

.x9o3dbc9s {
  d: path("M5.75 12.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m8 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M4 20.5c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75m0 0c0-2.25 1.75-3.75 4-3.75s4 1.5 4 3.75");
}

</style>
