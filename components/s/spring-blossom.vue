<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fukd2hq3y"/><path class="ds3qmebyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spring-blossom" /></template>
<style>
.ds3qmebyn {
  d: path("M2.5 21.5q3.5-6 8-8.5l4.75-5.25M10.5 13l-4-4.25m4 4.25l5.25 2.75");
}

.fukd2hq3y {
  d: path("M5.25 4.75a1.5 1.5 0 1 1 2.5 0a1.5 1.5 0 1 1 1 2.5a1.5 1.5 0 1 1-2.25 1.5a1.5 1.5 0 1 1-2.25-1.5a1.5 1.5 0 1 1 1-2.5m11 .5a1.5 1.5 0 1 1 2.5 0a1.5 1.5 0 1 1 1 2.5a1.5 1.5 0 1 1-2.25 1.5a1.5 1.5 0 1 1-2.25-1.5a1.5 1.5 0 1 1 1-2.5m-.5 10.5a1.5 1.5 0 1 1 2.5 0a1.5 1.5 0 1 1 1 2.5a1.5 1.5 0 1 1-2.25 1.5a1.5 1.5 0 1 1-2.25-1.5a1.5 1.5 0 1 1 1-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
