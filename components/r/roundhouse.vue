<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m108tcbda"/><path class="nrzgs4qct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roundhouse" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m108tcbda {
  d: path("M2.5 19.5v-10q9.5-8.5 19 0v10Z");
}

.nrzgs4qct {
  d: path("M6 19.5v-5a2 2 0 0 1 4 0v5m4 0v-5a2 2 0 0 1 4 0v5");
}

</style>
