<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-h3w6bca"/><path class="dnjnduz3q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:volleyball-set" /></template>
<style>
.dnjnduz3q {
  d: path("M15 3c-1.75 2.25-1.75 4.5 0 6m0 0c2-.5 4 .5 5.25 3M15 9c.25 2.25-2.5 3.5-5.25 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-h3w6bca {
  d: path("M9 9a6 6 0 1 0 12 0A6 6 0 1 0 9 9M3 21.5Q3.5 12 6.25 9");
}

</style>
