<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o91u6lfdw"/><path class="ncd__xouz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:safe-vault" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ncd__xouz {
  d: path("M6.5 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 0h.01m6.99-3v6m-11 5.5v2m11-2v2");
}

.o91u6lfdw {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v10a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16V6a3.5 3.5 0 0 1 3.5-3.5");
}

</style>
