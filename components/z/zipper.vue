<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="i9zi39qze"/><path class="v7t7q8bqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zipper" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9zi39qze {
  width: 3px;
  height: 3.25px;
  x: 10.5px;
  y: 2.75px;
  rx: 1px;
}

.v7t7q8bqv {
  d: path("M8.75 6h6.5q.75 0 .62.74l-.49 2.77q-.13.74-.88.74h-5q-.75 0-.88-.74l-.49-2.77Q8 6 8.75 6m0 4.25v11m6.5-11v11M8.75 13H11m4.25 2.25H13M8.75 17.5H11m4.25 2.25H13");
}

</style>
