<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ggbcuxbun"/><path class="kt5q1mbfk"/><path class="kncl_dbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prompt-copy" /></template>
<style>
.ggbcuxbun {
  d: path("M4.5 17.5V5A2.5 2.5 0 0 1 7 2.5h8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kncl_dbrk {
  d: path("M11.5 10.5h5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H13l-2 2v-2a1 1 0 0 1-.5-1v-3a1 1 0 0 1 1-1");
}

.kt5q1mbfk {
  d: path("M11.5 7h5a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-5A3.5 3.5 0 0 1 8 18v-7.5A3.5 3.5 0 0 1 11.5 7");
}

</style>
