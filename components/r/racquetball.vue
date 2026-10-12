<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c-62ubcle"/><circle class="b-a3wt_2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:racquetball" /></template>
<style>
.b-a3wt_2h {
  cx: 18.75px;
  cy: 17px;
  r: 2px;
}

.c-62ubcle {
  d: path("M9.5 2.75c3.5 0 6.25 2 6.25 4.75s-3.5 4.5-6.25 5.75c-2.75-1.25-6.25-3-6.25-5.75S6 2.75 9.5 2.75M5.75 7.5h7.5M9.5 4.75v6m0 2.5v8m0-.5c1.5.5 4 .25 4-1.5s-2.5-1.75-4-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
