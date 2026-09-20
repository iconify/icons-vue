<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eqcwclb9p"/><path class="o9risppvo"/><path class="kqgj1mbtk"/><path class="jl5_x8rdu"/><path class="lny_s1b9z"/><path class="ho29mccfb"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:starry-duotone-thin" /></template>
<style>
.eqcwclb9p {
  fill: currentColor;
  d: path("m7 5 3 3 -3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ho29mccfb {
  d: path("m12 10.5 2.5 2.5 -2.5 2.5L9.5 13Z");
}

.jl5_x8rdu {
  d: path("m7 5 3 3 -3 3 -3 -3Z");
}

.kqgj1mbtk {
  fill: currentColor;
  d: path("m12 10.5 2.5 2.5 -2.5 2.5L9.5 13Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lny_s1b9z {
  d: path("M16 3.5 18.5 6 16 8.5 13.5 6Z");
}

.o9risppvo {
  fill: currentColor;
  d: path("M16 3.5 18.5 6 16 8.5 13.5 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
