<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n13x6dbmu"/><path class="yff-74b6o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:music-theory-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n13x6dbmu {
  d: path("M4.5 19V5A2.5 2.5 0 0 1 7 2.5h12.5v19H7A2.5 2.5 0 0 1 4.5 19");
}

.yff-74b6o {
  d: path("M4.5 19A2.5 2.5 0 0 1 7 16.5h12.5m-7.5-3V5q3.25.75 1.5 3.25l-4 3a2.5 2.5 0 0 0 5 0a2.5 2.5 0 0 0-2.5-2.5");
}

</style>
