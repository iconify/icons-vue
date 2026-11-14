<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wh3ncvbwu"/><path class="iyy_4mslo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recursion" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyy_4mslo {
  d: path("m13.5 11.25l2 2l2-2");
}

.wh3ncvbwu {
  d: path("M3.5 13.25a8.5 8.5 0 0 1 17 0a6 6 0 0 1-12 0a3.5 3.5 0 0 1 7 0");
}

</style>
