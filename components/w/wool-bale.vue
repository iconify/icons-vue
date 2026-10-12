<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-9oeiaip"/><path class="olzq8_b3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wool-bale" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-9oeiaip {
  d: path("M2.75 9a2.31 2.31 0 0 1 4.62 0A2.31 2.31 0 0 1 12 9a2.31 2.31 0 0 1 4.62 0a2.31 2.31 0 0 1 4.63 0v10.5a1.75 1.75 0 0 1-1.75 1.75h-15a1.75 1.75 0 0 1-1.75-1.75Z");
}

.olzq8_b3s {
  d: path("M4.5 13.5q1.125-1.125 2.25 0M10.5 17q1.125-1.125 2.25 0m4.5-3.5q1.125-1.125 2.25 0m-11-3.75v11.5m7-11.5v11.5");
}

</style>
