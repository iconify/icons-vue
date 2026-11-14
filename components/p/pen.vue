<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lj2wmct9y"/><path class="bp81hr69e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pen" /></template>
<style>
.bp81hr69e {
  d: path("M10 11.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8 21h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lj2wmct9y {
  d: path("m13.924 4.572l3.56 3.834a2.63 2.63 0 0 1 .595 2.527l-1.525 5.183A2.625 2.625 0 0 1 14.036 18H9.964a2.625 2.625 0 0 1-2.518-1.884l-1.525-5.183a2.63 2.63 0 0 1 .595-2.527l3.56-3.834a2.625 2.625 0 0 1 3.848 0M12 2.5v7.25");
}

</style>
