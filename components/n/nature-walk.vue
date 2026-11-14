<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pj5m04b7u"/><path class="h508g34zb"/><path class="pyh7ohwot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nature-walk" /></template>
<style>
.h508g34zb {
  d: path("M9.5 21.5c0-6 4.5-8 2.5-16.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pj5m04b7u {
  d: path("M2.5 8.5q9.5-7 19 0M4.5 12l2 6.5h-4Zm0 6.5V21m15-9l2 6.5h-4Zm0 6.5V21");
}

.pyh7ohwot {
  d: path("M14.5 21.5c1-6 1-10.5-2.5-16.5");
}

</style>
