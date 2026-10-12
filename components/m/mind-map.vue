<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="xquhhsbdz"/><path class="b1hyqjbku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mind-map" /></template>
<style>
.b1hyqjbku {
  d: path("M15 12c1.25 0 1.25-6.25 2.5-6.25h3.75M15 12h6.25M15 12c1.25 0 1.25 6.25 2.5 6.25h3.75M8 12c-1.25 0-1.25-4-2.5-4H2.75M8 12c-1.25 0-1.25 4-2.5 4H2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xquhhsbdz {
  width: 7px;
  height: 4.5px;
  x: 8px;
  y: 9.75px;
  rx: 2.25px;
}

</style>
