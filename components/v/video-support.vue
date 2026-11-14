<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q4xw8cbec"/><path class="mn1kq48gk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:video-support" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mn1kq48gk {
  d: path("m15.829 6.585l2-1A1.5 1.5 0 0 1 20 6.927v3.146a1.5 1.5 0 0 1-2.171 1.342l-2-1A1.5 1.5 0 0 1 15 9.073V7.927a1.5 1.5 0 0 1 .829-1.342M17 17.25a2 2 0 0 1 4 0c0 1.35-2 1.65-2 2M19 22h.01");
}

.q4xw8cbec {
  d: path("M6 3.5h5.5A3.5 3.5 0 0 1 15 7v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 10V7A3.5 3.5 0 0 1 6 3.5");
}

</style>
