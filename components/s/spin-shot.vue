<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iy0w0cchs"/><path class="b1pgj34_r"/><path class="y90_y5blt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spin-shot" /></template>
<style>
.b1pgj34_r {
  d: path("M18.5 5.5a9 9 0 1 1-13 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iy0w0cchs {
  d: path("M7.75 12a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

.y90_y5blt {
  d: path("M3.25 5.5H5.5v2.25M8 10.5q4 2.75 8 0");
}

</style>
