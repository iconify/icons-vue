<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xenvd-bzf"/><path class="ifgaqkbho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:reset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ifgaqkbho {
  d: path("M14.25 2.25L12 4.5l2.25 2.25");
}

.xenvd-bzf {
  d: path("M3.5 13A8.5 8.5 0 1 0 12 4.5");
}

</style>
