<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sny_rbbsk"/><path class="g-994exmi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marker-square" /></template>
<style>
.g-994exmi {
  d: path("M11.25 7.5h1.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75h-1.5a1.75 1.75 0 0 1-1.75-1.75v-1.5a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sny_rbbsk {
  d: path("M6.625 3.5h10.75A2.625 2.625 0 0 1 20 6.125v7.75a2.625 2.625 0 0 1-2.625 2.625h-1.153a2.63 2.63 0 0 0-2.24 1.256l-.607.994a1.61 1.61 0 0 1-2.75 0l-.607-.994a2.63 2.63 0 0 0-2.24-1.256H6.625A2.625 2.625 0 0 1 4 13.875v-7.75A2.625 2.625 0 0 1 6.625 3.5");
}

</style>
