<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8w6tnbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skip-back" /></template>
<style>
.c8w6tnbxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.246 6.927l-5.198 3.639a1.75 1.75 0 0 0 0 2.868l5.198 3.639A1.75 1.75 0 0 0 19 15.639V8.361a1.75 1.75 0 0 0-2.754-1.434M5 5v14");
}

</style>
