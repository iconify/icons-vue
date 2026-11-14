<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lfhzgjner"/><path class="p1ar2cgtn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:press-vest" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lfhzgjner {
  d: path("M8.5 2.5H10L12 6l2-3.5h1.5c.25 3.5 1.5 6 4 7V20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20V9.5c2.5-1 3.75-3.5 4-7");
}

.p1ar2cgtn {
  d: path("M9.75 12.5h4.5A1.75 1.75 0 0 1 16 14.25v1A1.75 1.75 0 0 1 14.25 17h-4.5A1.75 1.75 0 0 1 8 15.25v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
