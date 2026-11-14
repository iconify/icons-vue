<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0_p-0b4j"/><path class="i048fzrgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meals-on-wheels" /></template>
<style>
.d0_p-0b4j {
  d: path("M5.125 10h6.75a2.625 2.625 0 0 1 2.625 2.625v1.75A2.625 2.625 0 0 1 11.875 17h-6.75A2.625 2.625 0 0 1 2.5 14.375v-1.75A2.625 2.625 0 0 1 5.125 10m9.375 2h4l3 3v2h-7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i048fzrgt {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M4 10a4.5 4.5 0 0 1 9 0M8.5 3v2.5");
}

</style>
