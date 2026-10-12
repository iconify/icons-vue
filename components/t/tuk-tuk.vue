<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="may72ccpz"/><path class="s2rv67buh"/><circle class="j1-unv-pk"/><rect class="yih46fnrn"/><rect class="o7t5thabx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuk-tuk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j1-unv-pk {
  cx: 12px;
  cy: 19.5px;
  r: 1.75px;
}

.may72ccpz {
  d: path("M4.5 3h15q1.25 0 1.04 1.23l-1.08 6.54q-.21 1.23-1.22 1.97l-1.73 1.27q-1.01.74-2.26.74h-4.5q-1.25 0-2.26-.74l-1.73-1.27Q4.75 12 4.54 10.77L3.46 4.23Q3.25 3 4.5 3");
}

.o7t5thabx {
  width: 3px;
  height: 3.75px;
  x: 17.5px;
  y: 17.5px;
  rx: 1.25px;
}

.s2rv67buh {
  d: path("M7.75 6h8.5q.75 0 .62.74l-.49 2.77q-.13.74-.88.74h-7q-.75 0-.88-.74l-.49-2.77Q7 6 7.75 6");
}

.yih46fnrn {
  width: 3px;
  height: 3.75px;
  x: 3.5px;
  y: 17.5px;
  rx: 1.25px;
}

</style>
