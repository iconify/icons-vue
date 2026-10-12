<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d3oqm-bjd"/><rect class="q4e8txbps"/><path class="pnkvqpbga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:town-house" /></template>
<style>
.d3oqm-bjd {
  d: path("M4.75 5.5h14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pnkvqpbga {
  d: path("M9 8.5v2.25m6-2.25v2.25M9 13v2.25m3.75 6V16.5h2.5v4.75");
}

.q4e8txbps {
  width: 12px;
  height: 15.75px;
  x: 6px;
  y: 5.5px;
  rx: 0.5px;
}

</style>
