<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ib6dlem5t"/><path class="jcttu4brj"/><path class="ejx-lm94j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oven-clock-sharp" /></template>
<style>
.ejx-lm94j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 11h10.5v6.75H6.75z");
}

.ib6dlem5t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 2.75h17.5v18.5H3.25zm0 5h17.5");
}

.jcttu4brj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 5.25h.01m3.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
