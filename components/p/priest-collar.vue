<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lqruq4dyu"/><rect class="f68z5pbkt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:priest-collar" /></template>
<style>
.f68z5pbkt {
  width: 2.5px;
  height: 2.75px;
  x: 10.75px;
  y: 14.75px;
  rx: 0.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqruq4dyu {
  d: path("M2.75 21.25V17c0-1.5 1-2.5 2.5-3L9 12.5q1.125 2.25 3 2.25c1.875 0 2.25-.75 3-2.25l3.75 1.5c1.5.5 2.5 1.5 2.5 3v4.25Z");
}

</style>
