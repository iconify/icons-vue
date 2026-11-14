<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yaqw_gxbu"/><path class="p5m1chsdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:scene-movie" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p5m1chsdn {
  d: path("M9.75 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4 6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-8 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.yaqw_gxbu {
  d: path("M2.5 11.5a9 9 0 1 0 18 0a9 9 0 1 0-18 0m9 9h10");
}

</style>
