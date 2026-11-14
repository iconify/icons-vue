<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wi4zxj8mf"/><path class="l21akjbyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-conservation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l21akjbyk {
  d: path("m13 19l5.5-3.5a1.75 1.75 0 0 1 2 2.75L15 21.5H2.5M14 2.5s-3.5 4-3.5 6a3.5 3.5 0 0 0 7 0c0-2-3.5-6-3.5-6");
}

.wi4zxj8mf {
  d: path("M2.5 14H6c1.5 0 3 1 4 2h3a1.5 1.5 0 0 1 0 3H9.5");
}

</style>
