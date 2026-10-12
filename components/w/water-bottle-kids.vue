<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7q5p0b1b"/><rect class="yum9okbdb"/><rect class="ceagy-bdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-bottle-kids" /></template>
<style>
.ceagy-bdy {
  width: 10px;
  height: 9.75px;
  x: 7px;
  y: 11.5px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k7q5p0b1b {
  d: path("M8.75 5.5V4.25a1.5 1.5 0 0 1 3 0V5.5m3 0V4l2-1.25");
}

.yum9okbdb {
  width: 7.5px;
  height: 3px;
  x: 8.25px;
  y: 5.5px;
  rx: 1.25px;
}

</style>
