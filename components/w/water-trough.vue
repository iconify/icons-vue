<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_1__5bcv"/><path class="k0srkbbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:water-trough" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_1__5bcv {
  d: path("M16.5 10V6a2 2 0 0 1 2-2h2.75m-18.5 6h18.5L20 19.5a2 2 0 0 1-2 1.75H6a2 2 0 0 1-2-1.75Z");
}

.k0srkbbmc {
  d: path("M5 13.5c1.25-1 2.5-1 3.5 0s2.25 1 3.5 0s2.25-1 3.5 0s2.25 1 3.5 0");
}

</style>
