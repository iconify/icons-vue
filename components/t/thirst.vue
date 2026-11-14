<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c4qm9fc7c"/><path class="lmyrboukj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thirst" /></template>
<style>
.c4qm9fc7c {
  d: path("M2.5 15.5c2.5-3.5 5.5-5 7.75-4.25L12 12l1.75-.75C16 10.5 19 12 21.5 15.5C19 19.25 15.5 21 12 21s-7-1.75-9.5-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmyrboukj {
  fill: currentColor;
  d: path("M6.5 15.5c2.5-.5 8.5-.5 11 0c-2 3-9 3-11 0m5.5-13c1.5 1.75 2.25 2.75 2.25 3.75c0 1.25-1 2.25-2.25 2.25s-2.25-1-2.25-2.25c0-1 .75-2 2.25-3.75");
}

</style>
