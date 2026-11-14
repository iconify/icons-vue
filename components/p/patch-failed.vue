<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajdpypb_x"/><path class="m8jlyk1wm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patch-failed" /></template>
<style>
.ajdpypb_x {
  d: path("m4.404 9.354l4.95-4.95a3 3 0 0 1 4.242 0a3 3 0 0 1 0 4.242l-4.95 4.95a3 3 0 0 1-4.242 0a3 3 0 0 1 0-4.242");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m8jlyk1wm {
  d: path("m6.525 7.939l1.414-1.414a1.5 1.5 0 0 1 2.122 0l1.414 1.414a1.5 1.5 0 0 1 0 2.122l-1.414 1.414a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122M15.5 15.5l5 5m0-5l-5 5");
}

</style>
