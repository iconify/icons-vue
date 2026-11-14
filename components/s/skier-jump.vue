<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p6em3cbra"/><path class="gibkbob0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skier-jump" /></template>
<style>
.gibkbob0y {
  d: path("m11.5 8l4 .75l4-1.25M11 15.25l9-3M2.5 20.5h5c2.5 0 3.75-.75 4.5-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p6em3cbra {
  d: path("M14.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0M16 7.5L14 11l2 2.5");
}

</style>
