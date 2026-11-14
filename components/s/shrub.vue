<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crvp5sghg"/><path class="ov7e4bc4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shrub" /></template>
<style>
.crvp5sghg {
  d: path("M3 19c-1-2.5-.5-5.5 2-6.5c-.5-3.5 2.5-6 5.5-5C12 5 16 5 17.5 8c2.5.5 4 3 3 5.5c1.5 2 1 4.5 0 5.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ov7e4bc4z {
  d: path("M7.5 15.5q1-2.5 3.5-3m2.5 3q2.5-.5 3.5-3");
}

</style>
