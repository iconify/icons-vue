<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yjubmeoko"/><path class="hd8p5_j3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swimsuit-racing" /></template>
<style>
.hd8p5_j3r {
  d: path("M6 12.5q6 2.5 12 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yjubmeoko {
  d: path("M8 3c0 3.5-2 6-2 9v2.5c2.5 2 4 4 4.5 6.5h3c.5-2.5 2-4.5 4.5-6.5V12c0-3-2-5.5-2-9c-.5 6-7.5 6-8 0");
}

</style>
