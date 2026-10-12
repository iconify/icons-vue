<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ezkjvrueb"/><path class="afgv-vh2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pharmacy-cross" /></template>
<style>
.afgv-vh2y {
  d: path("M11.5 8h1q.4 0 .4.4v2.3q0 .4.4.4h2.3q.4 0 .4.4v1q0 .4-.4.4h-2.3q-.4 0-.4.4v2.3q0 .4-.4.4h-1q-.4 0-.4-.4v-2.3q0-.4-.4-.4H8.4q-.4 0-.4-.4v-1q0-.4.4-.4h2.3q.4 0 .4-.4V8.4q0-.4.4-.4");
}

.ezkjvrueb {
  d: path("M10.5 3h3Q15 3 15 4.5v3Q15 9 16.5 9h3Q21 9 21 10.5v3q0 1.5-1.5 1.5h-3Q15 15 15 16.5v3q0 1.5-1.5 1.5h-3Q9 21 9 19.5v-3Q9 15 7.5 15h-3Q3 15 3 13.5v-3Q3 9 4.5 9h3Q9 9 9 7.5v-3Q9 3 10.5 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
