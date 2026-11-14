<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xo7hw3bam"/><path class="r53x24b-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-polo-referee" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r53x24b-h {
  d: path("M6.25 10.5L11 2.75l4.5 6.5M5 20.5q2.25-1.75 4.5 0t4.5 0t4.5 0");
}

.xo7hw3bam {
  d: path("M9 9.25h11V13h-7.25A3.75 3.75 0 1 1 9 9.25");
}

</style>
