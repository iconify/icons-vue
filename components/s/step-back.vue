<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="og4jscc7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:step-back" /></template>
<style>
.og4jscc7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.246 6.927l-5.198 3.639a1.75 1.75 0 0 0 0 2.868l5.198 3.639A1.75 1.75 0 0 0 15 15.639V8.361a1.75 1.75 0 0 0-2.754-1.434M19.5 5v14");
}

</style>
