<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5tg00bof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:step-forward" /></template>
<style>
.m5tg00bof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.754 6.927l5.198 3.639a1.75 1.75 0 0 1 0 2.868l-5.198 3.639A1.75 1.75 0 0 1 9 15.639V8.361a1.75 1.75 0 0 1 2.754-1.434M4.5 5v14");
}

</style>
