<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><path class="slms5hbma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:metro-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.la5qfrrxr {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2.5px;
}

.slms5hbma {
  d: path("M6.25 9.25h4.5m-4.5 5.5h3M14.5 10a2.75 2.75 0 0 1 0 4M17 8.25a5.25 5.25 0 0 1 0 7.5");
}

</style>
