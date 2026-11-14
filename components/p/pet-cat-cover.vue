<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x0p5hhd9g"/><path class="ev8aml37e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-cat-cover" /></template>
<style>
.ev8aml37e {
  d: path("M11 16h2l-1 1.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x0p5hhd9g {
  d: path("m4.5 4.5l4.5 4c1.5-.5 4.5-.5 6 0l4.5-4V13c0 4.5-3 7.5-7.5 7.5s-7.5-3-7.5-7.5ZM9 13h.01M15 13h.01");
}

</style>
