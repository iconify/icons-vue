<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o6h9f8b3a"/><path class="m0r0h2lds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:raincoat" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0r0h2lds {
  d: path("M7.5 7.5q3.5 2 7 0m-3.5 4v10m7.5-7.5l2.25 3.25a2.75 2.75 0 1 1-4.5 0Z");
}

.o6h9f8b3a {
  d: path("M13.503 21.5H3.5L4.5 9l3-1.5Q8 4 11 2.5q3 1.5 3.5 5l3 1.5l.186 2.33");
}

</style>
