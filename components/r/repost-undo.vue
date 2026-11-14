<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dxdxrabbj"/><path class="m-pq4db0y"/><path class="dz69gvw-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repost-undo" /></template>
<style>
.dxdxrabbj {
  d: path("M3.5 10.5V7a2 2 0 0 1 2-2h10");
}

.dz69gvw-b {
  d: path("M16.75 15.25L15 17l1.75 1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m-pq4db0y {
  d: path("M13 2.5L15.5 5L13 7.5m2.5 2.5v2.5q0 .155-.024.308M13.529 14.5H3.5M6 12l-2.5 2.5L6 17m10.5 4.5H19a2.25 2.25 0 0 0 0-4.5h-4");
}

</style>
