<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qebtl1bwc"/><path class="i8ozfdbgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:till-roll" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8ozfdbgi {
  d: path("M8 13.5h13.5l-1 1.75l1 1.75l-1 1.75l1 1.75H8M6.25 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M11 17h6.5");
}

.qebtl1bwc {
  d: path("M2.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

</style>
