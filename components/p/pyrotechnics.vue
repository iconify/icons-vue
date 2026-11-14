<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsmf2obew"/><path class="i8h54ybiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pyrotechnics" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8h54ybiv {
  d: path("M8 16.5V20a4 1.5 0 0 0 8 0v-3.5m-4-5v-9M10 12L5 5m9 7l5-7");
}

.lsmf2obew {
  d: path("M8 16.5a4 1.5 0 1 0 8 0a4 1.5 0 1 0-8 0");
}

</style>
