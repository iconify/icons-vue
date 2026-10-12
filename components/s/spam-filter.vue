<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="n98qq_4xx"/><path class="bj8sfcb8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spam-filter" /></template>
<style>
.bj8sfcb8f {
  d: path("m3.5 5l6 4.25l6-4.25m-3 11.25h8q.75 0 .18.48l-2.11 1.79Q18 19 18 19.75v.75q0 .75-.75.75h-1.5q-.75 0-.75-.75v-.75q0-.75-.57-1.23l-2.11-1.79q-.57-.48.18-.48");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n98qq_4xx {
  width: 13.5px;
  height: 10px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
