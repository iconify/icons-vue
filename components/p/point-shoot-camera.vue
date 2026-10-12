<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="no7ya_sep"/><rect class="nst5q0sxj"/><circle class="w4wqpfbkp"/><path class="xqntkvdws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:point-shoot-camera" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no7ya_sep {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 7.25px;
  rx: 2.5px;
}

.nst5q0sxj {
  width: 4px;
  height: 3px;
  x: 5px;
  y: 4.25px;
  rx: 1px;
}

.w4wqpfbkp {
  cx: 14.75px;
  cy: 13.5px;
  r: 3.5px;
}

.xqntkvdws {
  d: path("M5.75 10.5h2.5");
}

</style>
