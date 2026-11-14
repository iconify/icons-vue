<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n218y2bdj"/><path class="zzhqaebsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stage-lights" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n218y2bdj {
  d: path("M5.5 9V3h13v6");
}

.zzhqaebsg {
  d: path("M11.125 6h1.75A2.625 2.625 0 0 1 15.5 8.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 9.875v-1.25A2.625 2.625 0 0 1 11.125 6M8.5 15.5l-4.5 6m11.5-6l4.5 6");
}

</style>
