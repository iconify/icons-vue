<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bgdf-bcdg"/><path class="zour_mppf"/><path class="pu87a6buj"/><path class="maxs-gm0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pond-scene" /></template>
<style>
.bgdf-bcdg {
  d: path("M2.5 17a9.5 4 0 1 0 19 0a9.5 4 0 1 0-19 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.maxs-gm0m {
  d: path("M10.5 13q0-5.5 3-9");
}

.pu87a6buj {
  fill: currentColor;
  d: path("M7 3za1.25 1.25 0 0 1 1.25 1.25v3A1.25 1.25 0 0 1 7 8.5a1.25 1.25 0 0 1-1.25-1.25v-3A1.25 1.25 0 0 1 7 3");
}

.zour_mppf {
  d: path("M8 17q2-1.25 4 0t4 0M7 8.5v5");
}

</style>
