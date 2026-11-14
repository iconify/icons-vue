<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i0njbhb3m"/><path class="ymqe55c-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reptile-hide" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0njbhb3m {
  d: path("M5.5 6h13a2.5 6 0 0 1 0 12h-13");
}

.ymqe55c-d {
  d: path("M3 12a2.5 6 0 1 0 5 0a2.5 6 0 1 0-5 0m8 6v-3a3 3 0 0 1 6 0v3");
}

</style>
