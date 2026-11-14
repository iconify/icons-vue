<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re3nbbcdl"/><path class="mqvhsibot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:new-hire-paperwork" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mqvhsibot {
  d: path("M10.75 3h2.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25h-2.5A2.25 2.25 0 0 1 8.5 5.25A2.25 2.25 0 0 1 10.75 3m-1.5 7.25h1A1.75 1.75 0 0 1 12 12v.5a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 7.5 12.5V12a1.75 1.75 0 0 1 1.75-1.75m5.5 2h1.75m-9 5h9");
}

.re3nbbcdl {
  d: path("M8.5 5v-.5A1.5 1.5 0 0 1 10 3h4a1.5 1.5 0 0 1 1.5 1.5V5h2a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2Z");
}

</style>
