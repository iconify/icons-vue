<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d48nsvcbr"/><path class="vo45e0eun"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vegan-restaurant" /></template>
<style>
.d48nsvcbr {
  d: path("M11.704 20.5H3V10l9-6.5l9 6.5v1.696");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vo45e0eun {
  d: path("M8.25 14h1A1.75 1.75 0 0 1 11 15.75v3a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 8.25 14m6.25 7.5c0-4.5 2.5-7 7-7c0 4.5-2.5 7-7 7m0 0l4-4");
}

</style>
