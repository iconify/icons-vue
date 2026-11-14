<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_axcacrg"/><path class="tbnsj3b0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:velodrome" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n_axcacrg {
  d: path("M8 6.5h8a5.5 5.5 0 0 1 5.5 5.5a5.5 5.5 0 0 1-5.5 5.5H8A5.5 5.5 0 0 1 2.5 12A5.5 5.5 0 0 1 8 6.5");
}

.tbnsj3b0z {
  d: path("M8.5 10.25h7A1.75 1.75 0 0 1 17.25 12a1.75 1.75 0 0 1-1.75 1.75h-7A1.75 1.75 0 0 1 6.75 12a1.75 1.75 0 0 1 1.75-1.75M12 6.5v3.75");
}

</style>
