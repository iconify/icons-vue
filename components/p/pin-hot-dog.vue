<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="utrhhsbxt"/><path class="i_7dmc9lu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-hot-dog" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_7dmc9lu {
  d: path("M7.5 12q1.25-1 2.5 0t2.5 0t2.5 0t2.5 0");
}

.utrhhsbxt {
  d: path("M5.5 9h13a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3a3 3 0 0 1 3-3M6 9c0-2 2-3.5 4.5-3.5h3C16 5.5 18 7 18 9M6 15c0 2 2 3.5 4.5 3.5h3C16 18.5 18 17 18 15");
}

</style>
