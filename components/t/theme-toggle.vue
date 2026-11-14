<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jq91eijwj"/><path class="dsvzlvb9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:theme-toggle" /></template>
<style>
.dsvzlvb9u {
  d: path("M17.25 9a3.25 3.25 0 1 0 1.5 5a2.75 2.75 0 0 1-1.5-5M8.5 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jq91eijwj {
  d: path("M8.5 6h7a6 6 0 0 1 6 6a6 6 0 0 1-6 6h-7a6 6 0 0 1-6-6a6 6 0 0 1 6-6");
}

</style>
