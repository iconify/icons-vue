<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c0h77ov1k"/><path class="rl_hvla9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-department-map" /></template>
<style>
.c0h77ov1k {
  d: path("M11.764 19.666L8.5 18.5l-6 2.5V5.5l6-2.5l7 2.5l6-2.5v8.867M8.5 3v15.5m7-13v5.3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rl_hvla9b {
  d: path("M18 16.25v-.75a1.25 1.25 0 1 0-1.25-1.25m1.25 2l3.25 3q.5 1.25-.5 1.25M18 16.25l-3.25 3q-.5 1.25.5 1.25m0 0h5.5");
}

</style>
