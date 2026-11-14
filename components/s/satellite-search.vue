<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-9yplbyp"/><path class="qh215y0gi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:satellite-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-9yplbyp {
  d: path("m8.525 9.939l1.414-1.414a1.5 1.5 0 0 1 2.122 0l1.414 1.414a1.5 1.5 0 0 1 0 2.122l-1.414 1.414a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122m-4.243 4.95l.708-.707a1.5 1.5 0 0 1 2.121 0l.707.707a1.5 1.5 0 0 1 0 2.121l-.707.708a1.5 1.5 0 0 1-2.121 0l-.708-.708a1.5 1.5 0 0 1 0-2.121m9.9-9.899l.707-.708a1.5 1.5 0 0 1 2.121 0l.708.708a1.5 1.5 0 0 1 0 2.121l-.708.707a1.5 1.5 0 0 1-2.121 0l-.707-.707a1.5 1.5 0 0 1 0-2.121M6.5 15.5L8 14m6-6l1.5-1.5");
}

.qh215y0gi {
  d: path("M5 8.5q4.25.75 3.5-3.5m-.75 2.75L9 9m6.25 8.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
