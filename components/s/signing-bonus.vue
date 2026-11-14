<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vb8tq0bwj"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signing-bonus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.vb8tq0bwj {
  d: path("M3 15C5 10 6 4.5 8 5s-.5 9 1.5 9.5C11 15 12 9 14 9.5c1.5.5 2 1.5 4.5 0m-16 9H11m3-.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
