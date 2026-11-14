<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xgpwmubmc"/><path class="j6vmkybbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6vmkybbd {
  d: path("M14.25 8.25c0-2.25-.5-3.75 1.5-5.75");
}

.xgpwmubmc {
  d: path("M3 9q2.25-2.25 4.5 0T12 9t4.5 0T21 9v10.5c0 1.1-.9 2-2 2H5c-1.1 0-2-.9-2-2Zm0 6h18");
}

</style>
