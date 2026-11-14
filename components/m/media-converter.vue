<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m7aiy7upn"/><path class="o8snzqixx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:media-converter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m7aiy7upn {
  d: path("M6 11h12a3.5 3.5 0 0 1 3.5 3.5v2A3.5 3.5 0 0 1 18 20H6a3.5 3.5 0 0 1-3.5-3.5v-2A3.5 3.5 0 0 1 6 11");
}

.o8snzqixx {
  d: path("M7 13.75h1a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5H7a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5m9 0h1a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5M5 5.5h14m-11.5-2L5 5.5l2.5 2m9-4l2.5 2l-2.5 2");
}

</style>
