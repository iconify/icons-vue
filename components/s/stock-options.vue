<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qe97cg-lx"/><path class="pd44ehbxj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:stock-options" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pd44ehbxj {
  d: path("m5.5 17.5l4-4l3 2l3.75-6.25m-.75-2.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M18.25 6v1.5");
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

</style>
