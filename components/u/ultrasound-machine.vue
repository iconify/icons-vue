<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pr8x98bhj"/><path class="rlyu24o2l"/><path class="jz4aggdau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ultrasound-machine" /></template>
<style>
.jz4aggdau {
  d: path("m14.143 14.935l3.464-2l3.25 5.63l-3.464 2ZM19 19.75c.5 1.25 1.75 1.75 2.75 1.25");
}

.pr8x98bhj {
  d: path("M11.2 15.5H2.5V3h17v7.7M11 15.5v6m-4 0h6");
}

.rlyu24o2l {
  fill: currentColor;
  d: path("M14.874 11.295L11 5l-4 6.5q.333.21.686.384t.723.31q.369.136.75.232q.382.097.772.153q.389.056.782.071q.394.015.787-.011q.392-.026.78-.093q.388-.068.767-.175");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
