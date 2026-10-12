<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7uv0ibtf"/><rect class="beuzekcyu"/><rect class="xil365bwt"/><rect class="qb23qtbfj"/><path class="taxmbub4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pharmacy-counter" /></template>
<style>
.beuzekcyu {
  width: 3.5px;
  height: 3.5px;
  x: 4.25px;
  y: 10px;
  rx: 1px;
}

.e7uv0ibtf {
  d: path("M11.4 3.25h1.2q.5 0 .5.5V4.9q0 .5.5.5h1.15q.5 0 .5.5v1.2q0 .5-.5.5H13.6q-.5 0-.5.5v1.15q0 .5-.5.5h-1.2q-.5 0-.5-.5V8.1q0-.5-.5-.5H9.25q-.5 0-.5-.5V5.9q0-.5.5-.5h1.15q.5 0 .5-.5V3.75q0-.5.5-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qb23qtbfj {
  width: 18.5px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 1.5px;
}

.taxmbub4q {
  d: path("M6 17h12");
}

.xil365bwt {
  width: 3.5px;
  height: 2.5px;
  x: 16.25px;
  y: 11px;
  rx: 1px;
}

</style>
