<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="otocwx4zv"/><path class="h06wv9b3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ringette-ring" /></template>
<style>
.h06wv9b3d {
  d: path("M7 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0M20.5 2.5l-8 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.otocwx4zv {
  d: path("M4 15a5 5 0 1 0 10 0a5 5 0 1 0-10 0");
}

</style>
