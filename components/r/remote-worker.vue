<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="hajmoyu0i"/><rect class="ry1ztcbjt"/><path class="sj0eok4lr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:remote-worker" /></template>
<style>
.hajmoyu0i {
  cx: 12px;
  cy: 8.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ry1ztcbjt {
  width: 11px;
  height: 5.25px;
  x: 6.5px;
  y: 13.5px;
  rx: 1px;
}

.sj0eok4lr {
  d: path("M3.75 21.25h16.5M2.75 10L12 2.75L21.25 10");
}

</style>
