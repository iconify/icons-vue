<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hjru5mbwv"/><path class="zcofsyb1q"/><path class="nhh409ydq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mosquito-net" /></template>
<style>
.hjru5mbwv {
  cx: 12px;
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

.nhh409ydq {
  d: path("M10.25 12.75Q9.5 15 9.5 17.25m4.25-4.5q.75 2.25.75 4.5m-11.75 0h18.5M5 17.25v3.5m14-3.5v3.5");
}

.zcofsyb1q {
  d: path("M12 5.25c-1 4.75-8 7.25-8.75 12h17.5C20 12.5 13 10 12 5.25");
}

</style>
