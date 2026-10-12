<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="l7t-2o-_e"/><circle class="zv6cqnbnp"/><path class="f17p0yzgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-square" /></template>
<style>
.f17p0yzgj {
  d: path("M6.75 21.25c.6-2.75 2.75-4.5 5.25-4.5s4.65 1.75 5.25 4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l7t-2o-_e {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 4px;
}

.zv6cqnbnp {
  cx: 12px;
  cy: 10px;
  r: 3px;
}

</style>
