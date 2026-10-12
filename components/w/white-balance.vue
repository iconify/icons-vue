<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="la5qfrrxr"/><path class="mo06-hbnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:white-balance" /></template>
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

.mo06-hbnp {
  d: path("M5.75 9.25L7 14.75l1.5-4l1.5 4l1.25-5.5m2.75 5.5v-5.5h1.9a1.35 1.35 0 0 1 0 2.75H14h2.15a1.4 1.4 0 0 1 0 2.75Z");
}

</style>
