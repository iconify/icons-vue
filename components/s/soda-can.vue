<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="o2b98om6d"/><path class="h1r6dobeh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soda-can" /></template>
<style>
.h1r6dobeh {
  d: path("M8.5 2.75h7M6 14q3-2.25 6 0c3 2.25 4 1.5 6 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2b98om6d {
  width: 12px;
  height: 16px;
  x: 6px;
  y: 5.25px;
  rx: 2.25px;
}

</style>
