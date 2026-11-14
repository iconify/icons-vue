<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9af6cclp"/><path class="yet53acxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smell-sense" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9af6cclp {
  d: path("M4 2.5c1.5 4.5 5.5 8.5 7 12c1 2.5-.5 4-2.5 4c-1 0-2 1-2 3");
}

.yet53acxv {
  d: path("M8.5 18.5c-2-.5-2.25-3-.5-3.5m7 0c-1.5-1.5 1.5-2 0-3.5s1.5-2 0-3.5s1.5-2 0-3.5M19.5 15c-1.5-1.5 1.5-2 0-3.5s1.5-2 0-3.5s1.5-2 0-3.5");
}

</style>
