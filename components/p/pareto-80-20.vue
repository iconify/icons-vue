<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m6fyfxb1r"/><path class="ujzcsac9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pareto-80-20" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m6fyfxb1r {
  fill: currentColor;
  d: path("M4.25 8zA1.25 1.25 0 0 1 5.5 9.25v10.5A1.25 1.25 0 0 1 4.25 21A1.25 1.25 0 0 1 3 19.75V9.25A1.25 1.25 0 0 1 4.25 8m5 3za1.25 1.25 0 0 1 1.25 1.25v7.5A1.25 1.25 0 0 1 9.25 21A1.25 1.25 0 0 1 8 19.75v-7.5A1.25 1.25 0 0 1 9.25 11m5 3za1.25 1.25 0 0 1 1.25 1.25v4.5A1.25 1.25 0 0 1 14.25 21A1.25 1.25 0 0 1 13 19.75v-4.5A1.25 1.25 0 0 1 14.25 14m5 2za1.25 1.25 0 0 1 1.25 1.25v2.5A1.25 1.25 0 0 1 19.25 21A1.25 1.25 0 0 1 18 19.75v-2.5A1.25 1.25 0 0 1 19.25 16");
}

.ujzcsac9r {
  d: path("M4.25 5C8 3.25 13 2.5 20.5 2.5");
}

</style>
