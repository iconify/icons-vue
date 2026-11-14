<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2-ym-b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tree-shaking" /></template>
<style>
.a2-ym-b6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.221 4.209l3.198 4.477A.515.515 0 0 1 14 9.5a.58.58 0 0 0-.504.868l2.222 3.888a1.5 1.5 0 0 1-1.303 2.244h-8.83a1.5 1.5 0 0 1-1.303-2.244l2.222-3.888A.58.58 0 0 0 6 9.5a.515.515 0 0 1-.419-.814l3.198-4.477a1.5 1.5 0 0 1 2.442 0M10 16.5v5m8-15l2.5 2m-1.5 3l2.5 2m-2 5l2 2");
}

</style>
