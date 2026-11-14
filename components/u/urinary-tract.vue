<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r_2-c0dwh"/><path class="yga4ootee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:urinary-tract" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r_2-c0dwh {
  d: path("M6 2.75c-2 0-3.25 1.5-3.25 3.5S4 9.75 6 9.75c1 0 1.75-.5 1.5-1.5c-.25-.75-1-1.25-1-2s.75-1.25 1-2c.25-1-.5-1.5-1.5-1.5m12 7c2 0 3.25-1.5 3.25-3.5S20 2.75 18 2.75c-1 0-1.75.5-1.5 1.5c.25.75 1 1.25 1 2s-.75 1.25-1 2c-.25 1 .5 1.5 1.5 1.5m-9 8.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.yga4ootee {
  d: path("M6.5 6.25c2.5 2.25 3.75 5.25 4 9.25m7-9.25c-2.5 2.25-3.75 5.25-4 9.25");
}

</style>
