<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="rit15jh4l"/><path class="j-72f2a6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tractor-tire" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-72f2a6j {
  d: path("m6 5.5l6 3l6-3m-12 5l6 3l6-3m-12 5l6 3l6-3M2.75 12H6m12 0h3.25");
}

.rit15jh4l {
  width: 12px;
  height: 18.5px;
  x: 6px;
  y: 2.75px;
  rx: 3px;
}

</style>
