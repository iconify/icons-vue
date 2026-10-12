<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a62s6bcol"/><path class="c-vytw1jg"/><circle class="zur2nlbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:turban-pagri" /></template>
<style>
.a62s6bcol {
  d: path("M3.25 14.5C3.25 9 7 5.75 12 5.75S20.75 9 20.75 14.5V18a1.5 1.5 0 0 1-1.5 1.5H4.75a1.5 1.5 0 0 1-1.5-1.5Z");
}

.c-vytw1jg {
  d: path("M5 13c3 1 6 3.5 7 6.5m7-6.5c-3 1-6 3.5-7 6.5m0-9.75c-1.25-1.75-1.25-4.75.75-7c1 2.5.75 5-.75 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zur2nlbbt {
  cx: 12px;
  cy: 11.5px;
  r: 1.25px;
}

</style>
