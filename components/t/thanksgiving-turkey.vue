<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qgm-r29oi"/><path class="i66jnwbmu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thanksgiving-turkey" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i66jnwbmu {
  d: path("M10.6 11.25a2 2 0 1 1 2.8 0a4.25 4.5 0 1 1-2.8 0m.15 8.75v1.25m2.5-1.25v1.25");
}

.qgm-r29oi {
  d: path("M7.17 11.71a2.75 2.75 0 0 1-3.86-1.04a2.75 2.75 0 0 1 3.86 1.04m1.29-2.25a2.75 2.75 0 0 1-2.82-2.82a2.75 2.75 0 0 1 2.82 2.82m2.25-1.29a2.75 2.75 0 0 1-1.04-3.86a2.75 2.75 0 0 1 1.04 3.86m2.58 0a2.75 2.75 0 0 1 1.04-3.86a2.75 2.75 0 0 1-1.04 3.86m2.25 1.29a2.75 2.75 0 0 1 2.82-2.82a2.75 2.75 0 0 1-2.82 2.82m1.29 2.25a2.75 2.75 0 0 1 3.86-1.04a2.75 2.75 0 0 1-3.86 1.04");
}

</style>
