<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="p8ypvob7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:width-limit" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p8ypvob7c {
  d: path("M5.75 10.5v3q0 .75.56.25l1.38-1.25q.56-.5 0-1l-1.38-1.25q-.56-.5-.56.25m12.5 0v3q0 .75-.56.25l-1.38-1.25q-.56-.5 0-1l1.38-1.25q.56-.5.56.25M12 8.5v7");
}

</style>
