<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="b6f2r6r8q"/><rect class="d4ky7wbyv"/><path class="qi_u1r7gs"/><circle class="h-auvl8jn"/><rect class="yj3f84bjk"/><path class="lgl_4pl0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:parent-holding-hand" /></template>
<style>
.b6f2r6r8q {
  cx: 7px;
  cy: 4.5px;
  r: 1.75px;
}

.d4ky7wbyv {
  width: 5px;
  height: 6.5px;
  x: 4.5px;
  y: 8.75px;
  rx: 2.25px;
}

.h-auvl8jn {
  cx: 16.75px;
  cy: 10px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgl_4pl0t {
  d: path("M15.5 17.5v3.75M18 17.5v3.75M9.5 10.5q3 0 4.5 2.25");
}

.qi_u1r7gs {
  d: path("M5.75 15.25v6m2.5-6v6");
}

.yj3f84bjk {
  width: 4px;
  height: 5px;
  x: 14.75px;
  y: 12.75px;
  rx: 2px;
}

</style>
