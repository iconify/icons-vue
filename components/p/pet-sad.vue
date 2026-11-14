<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fkit1lrbu"/><path class="ez_pnccrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-sad" /></template>
<style>
.ez_pnccrj {
  d: path("M9 17.75q3-2.25 6 0");
}

.fkit1lrbu {
  d: path("m4.5 3.5l4 3.5a8.5 8.5 0 0 1 7 0l4-3.5l.5 6.5a8.5 8.5 0 1 1-16 0Zm3 10l2.5-1m6.5 1l-2.5-1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
