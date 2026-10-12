<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m2lk1bclp"/><path class="nyw55x_no"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tetris-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m2lk1bclp {
  d: path("M10.25 9h3.5Q15 9 15 10.25v3.5Q15 15 16.25 15h3.5Q21 15 21 16.25v3.5Q21 21 19.75 21H4.25Q3 21 3 19.75v-3.5Q3 15 4.25 15h3.5Q9 15 9 13.75v-3.5Q9 9 10.25 9M9 15v6m6-6v6m-6-6h6");
}

.nyw55x_no {
  d: path("M4.25 3h15.5Q21 3 21 4.25v9.5Q21 15 19.75 15h-3.5Q15 15 15 13.75v-3.5Q15 9 13.75 9h-9.5Q3 9 3 7.75v-3.5Q3 3 4.25 3M9 3v6m6-6v6m0 0h6");
}

</style>
