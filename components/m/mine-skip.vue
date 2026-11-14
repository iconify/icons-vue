<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hqf4sobqj"/><path class="z5ic6eb9s"/><path class="s9unfnbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mine-skip" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqf4sobqj {
  fill: currentColor;
  d: path("M6.579 15h10.842a2.29 2.29 0 0 1 2.079 3.25l-.796 1.725A2.63 2.63 0 0 1 16.32 21.5H7.68a2.63 2.63 0 0 1-2.384-1.525L4.5 18.25A2.29 2.29 0 0 1 6.579 15");
}

.s9unfnbyy {
  d: path("m4 15l8-4.25L20 15");
}

.z5ic6eb9s {
  d: path("M13.75 2v7a1.75 1.75 0 0 1-3.5 0V8");
}

</style>
