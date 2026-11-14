<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sx1x5nbhe"/><path class="n0gbwjutu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skin-layers" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n0gbwjutu {
  d: path("M3 11.5q3.375-2.25 6.75 0t6.75 0c1.75-1.25 3.25-1.5 4.5-1m-18 6h18");
}

.sx1x5nbhe {
  d: path("M3 6.5q3.375-2.25 6.75 0t6.75 0c1.75-1.25 3.25-1.5 4.5-1v14c0 1.1-.9 2-2 2H5c-1.1 0-2-.9-2-2Z");
}

</style>
