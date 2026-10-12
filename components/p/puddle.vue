<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a6ctoz2fm"/><path class="mklvdob-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:puddle" /></template>
<style>
.a6ctoz2fm {
  d: path("M2.75 17.5a9.25 3.75 0 1 0 18.5 0a9.25 3.75 0 1 0-18.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mklvdob-k {
  d: path("M8.5 17.25a3.5 1 0 0 0 7 0M11.72 3.41L9.79 7.09a2.5 2.5 0 1 0 4.42 0l-1.93-3.68q-.28-.53-.56 0");
}

</style>
