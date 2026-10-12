<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a-yzuab_q"/><path class="ba1o5ybvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:upcycle" /></template>
<style>
.a-yzuab_q {
  width: 10px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 2px;
}

.ba1o5ybvo {
  d: path("M7.75 13.25V11a6 6 0 0 1 6-6h4M15.5 2.75L17.75 5L15.5 7.25M17.25 13q.45 3.3 3.75 3.75q-3.3.45-3.75 3.75q-.45-3.3-3.75-3.75q3.3-.45 3.75-3.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
