<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ohix6tbxa"/><path class="iflquszho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:spatial-stylus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iflquszho {
  d: path("m2.5 14.25l4 2.25l4-2.25m-4 2.25V21m7.875-9.375l1.539-.513a1.5 1.5 0 0 0 .586-.362l4.189-4.189a1.5 1.5 0 0 0 0-2.122l-.378-.378a1.5 1.5 0 0 0-2.122 0L14 8.25a1.5 1.5 0 0 0-.362.586l-.513 1.539a.988.988 0 0 0 1.25 1.25M13.75 8.5l2.5 2.5");
}

.ohix6tbxa {
  d: path("m7.235 12.414l2.5 1.406a1.5 1.5 0 0 1 .765 1.307v2.746a1.5 1.5 0 0 1-.765 1.307l-2.5 1.406a1.5 1.5 0 0 1-1.47 0l-2.5-1.406a1.5 1.5 0 0 1-.765-1.307v-2.746a1.5 1.5 0 0 1 .765-1.307l2.5-1.406a1.5 1.5 0 0 1 1.47 0");
}

</style>
