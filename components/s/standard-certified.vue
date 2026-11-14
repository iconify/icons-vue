<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="prgcd4b-o"/><path class="r6ni9ykjg"/><path class="zebutmbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:standard-certified" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.prgcd4b-o {
  d: path("M8.375 3h.948a1.5 1.5 0 0 1 1.342.829l.46.921a.978.978 0 0 0 1.75 0l.46-.921A1.5 1.5 0 0 1 14.677 3h.948a1.197 1.197 0 0 1 1.085 1.701l-2.057 4.431a1.5 1.5 0 0 1-1.36.868h-2.586a1.5 1.5 0 0 1-1.36-.868L7.29 4.701A1.197 1.197 0 0 1 8.375 3");
}

.r6ni9ykjg {
  d: path("M6.5 15.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

.zebutmbne {
  d: path("m9.75 15.5l1.75 1.75l3-3.25");
}

</style>
