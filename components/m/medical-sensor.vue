<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bhmhagbrg"/><path class="go1q4nb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-sensor" /></template>
<style>
.bhmhagbrg {
  d: path("M7.125 10.5h3.25A2.625 2.625 0 0 1 13 13.125v3.25A2.625 2.625 0 0 1 10.375 19h-3.25A2.625 2.625 0 0 1 4.5 16.375v-3.25A2.625 2.625 0 0 1 7.125 10.5");
}

.go1q4nb6m {
  d: path("M7.25 14.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M2.5 13h2m-2 3.5h2M7 19v2m3.5-2v2M13 7a3.5 3.5 0 0 1 3.5 3.5M13 3.75a6.75 6.75 0 0 1 6.75 6.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
