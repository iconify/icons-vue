<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u1od_cciz"/><path class="nwplbdcqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ruler-office" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nwplbdcqv {
  d: path("M6 13.25v2.5m3-2.5v1.5m3-1.5v2.5m3-2.5v1.5m3-1.5v2.5M7.75 5H20.5q.75 0 .75.75v2.5q0 .75-.75.75H7.75Q7 9 6.34 8.65l-2.43-1.3q-.66-.35 0-.7l2.43-1.3Q7 5 7.75 5M8 5v4");
}

.u1od_cciz {
  width: 18.5px;
  height: 6px;
  x: 2.75px;
  y: 13.25px;
  rx: 1.5px;
}

</style>
