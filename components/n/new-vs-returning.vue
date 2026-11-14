<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="us56m6b9i"/><path class="hgliz9hmv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:new-vs-returning" /></template>
<style>
.hgliz9hmv {
  d: path("m18.75 10.25l2.25 2l1-2.5m-13-1a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-2.25 8.5c0-2.5 2.25-4 4.75-4c1.469 0 2.851.518 3.742 1.452M18 14.5v7M14.5 18h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us56m6b9i {
  d: path("M8.922 20.457a9 9 0 1 1 12.044-9.241");
}

</style>
