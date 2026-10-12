<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yedn97mkn"/><path class="wtruwobgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nut-sharp" /></template>
<style>
.wtruwobgh {
  d: path("M15.75 12a3.75 3.75 0 1 1-7.5 0a3.75 3.75 0 1 1 7.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yedn97mkn {
  d: path("m13.52 3.63l4.97 2.87l1.52.88v9.25l-1.52.87l-4.97 2.88l-1.52.87l-1.52-.87l-4.97-2.88l-1.52-.87V7.37l1.52-.87l4.97-2.88L12 2.75z");
}

</style>
