<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="itxcm0bbl"/><circle class="zv6cqnbnp"/><path class="f17p0yzgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-square-sharp" /></template>
<style>
.f17p0yzgj {
  d: path("M6.75 21.25c.6-2.75 2.75-4.5 5.25-4.5s4.65 1.75 5.25 4.5");
}

.itxcm0bbl {
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zv6cqnbnp {
  cx: 12px;
  cy: 10px;
  r: 3px;
}

</style>
