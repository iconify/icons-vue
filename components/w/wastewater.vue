<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f2d_89bhe"/><path class="rcmuyobly"/><path class="rnmrtlh1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wastewater" /></template>
<style>
.f2d_89bhe {
  d: path("M10.5 2.5s-7 7-7 11.5a7 7 0 0 0 14 0c0-4.5-7-11.5-7-11.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rcmuyobly {
  d: path("M6.5 15c1.5-1.5 2.5-1.5 4 0s2.5 1.5 4 0");
}

.rnmrtlh1s {
  fill: currentColor;
  d: path("M19.25 12.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-.5 4.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-2.25 3.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
