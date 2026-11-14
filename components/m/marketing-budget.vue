<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="woctahbxr"/><path class="c-ibc-_xn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marketing-budget" /></template>
<style>
.c-ibc-_xn {
  d: path("M13.5 10.25v-8a8 8 0 0 1 8 8Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.woctahbxr {
  d: path("M10.75 5a8 8 0 1 0 8 8h-8Z");
}

</style>
