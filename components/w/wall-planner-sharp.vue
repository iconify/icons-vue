<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="thi123b8x"/><path class="d7h7k6b1f"/><path class="zjsvsnq6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wall-planner-sharp" /></template>
<style>
.d7h7k6b1f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13.25h.01");
}

.thi123b8x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v16.5H2.75zm0 4.75h18.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zjsvsnq6j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 13.25h6.25m-11 3.5h11.5");
}

</style>
