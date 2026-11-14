<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4nnaobsq"/><path class="c3z1rd30e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pulp-cap" /></template>
<style>
.c3z1rd30e {
  d: path("M8 10q4-4.5 8 0m-6.5 3.75a2.5 2.5 0 0 1 5 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u4nnaobsq {
  d: path("M8 2.5c2 0 2.5 1 4 1s2-1 4-1c2.75 0 4 2 4 5s-1.25 4.5-1.75 7L17.5 20c-.25 1.5-2.25 1.5-2.5 0l-1-2.75c-.5-1-3.5-1-4 0L9 20c-.25 1.5-2.25 1.5-2.5 0l-.75-5.5C5.25 12 4 10.5 4 7.5s1.25-5 4-5");
}

</style>
