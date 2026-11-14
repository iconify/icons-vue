<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f5g1dbbam"/><path class="ruit5cbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:telecom-van" /></template>
<style>
.f5g1dbbam {
  d: path("M2.5 16.5V9a2 2 0 0 1 2-2H14l4 4h1.5a2 2 0 0 1 2 2v3.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ruit5cbro {
  d: path("M4.75 18.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m10 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M4.5 4.25H13M13 7v4h5");
}

</style>
