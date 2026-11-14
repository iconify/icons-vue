<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i8vyupaea"/><path class="ckaz6ab3p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tyre-pressure-gauge" /></template>
<style>
.ckaz6ab3p {
  d: path("M11 16.5V18a2 2 0 0 0 2 2h3m1.5-1.5H19a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-1.5A1.5 1.5 0 0 1 16 20a1.5 1.5 0 0 1 1.5-1.5m-6.5-9l2.75-2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8vyupaea {
  d: path("M4 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0");
}

</style>
