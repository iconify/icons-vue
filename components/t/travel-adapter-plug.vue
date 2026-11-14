<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dpme1sb0v"/><path class="yfewu9b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:travel-adapter-plug" /></template>
<style>
.dpme1sb0v {
  d: path("M7.5 9h9a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 18v-5.5A3.5 3.5 0 0 1 7.5 9M9 3v6m6-6v6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfewu9b_t {
  d: path("M9 15.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
