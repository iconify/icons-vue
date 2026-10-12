<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="p9ipau0kd"/><path class="vf1f99d6u"/><circle class="ggsmnab5p"/><path class="sum-9ccvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:road-barrier" /></template>
<style>
.ggsmnab5p {
  cx: 6px;
  cy: 4px;
  r: 1.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p9ipau0kd {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 8px;
  rx: 1px;
}

.sum-9ccvt {
  d: path("M6 5.25V8m-1.5 4l4 9.25m0-9.25l-4 9.25m11-9.25l4 9.25m0-9.25l-4 9.25");
}

.vf1f99d6u {
  d: path("M7.5 12L10 8m3.5 4L16 8");
}

</style>
