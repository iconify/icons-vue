<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajdpypb_x"/><path class="o4c2-5hiw"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:patch-pending" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

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

.o4c2-5hiw {
  d: path("m6.525 7.939l1.414-1.414a1.5 1.5 0 0 1 2.122 0l1.414 1.414a1.5 1.5 0 0 1 0 2.122l-1.414 1.414a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
