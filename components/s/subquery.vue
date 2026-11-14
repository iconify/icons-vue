<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ghdle1bhl"/><path class="umumw6a-w"/><path class="quwj-3b0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:subquery" /></template>
<style>
.ghdle1bhl {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-8.25A4.375 4.375 0 0 1 6.875 3.5M2.5 8h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.quwj-3b0b {
  d: path("M13 14.75L12 16l1 1.25m3.5-2.5l1 1.25l-1 1.25");
}

.umumw6a-w {
  d: path("M5 10.5L7 12l-2 1.5M5 17h2.5m5.125-6.5h4.25a2.625 2.625 0 0 1 2.625 2.625v2.75a2.625 2.625 0 0 1-2.625 2.625h-4.25A2.625 2.625 0 0 1 10 15.875v-2.75a2.625 2.625 0 0 1 2.625-2.625M10 13h9.5");
}

</style>
