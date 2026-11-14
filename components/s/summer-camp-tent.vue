<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hcadwabkv"/><path class="vs5j3vbrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:summer-camp-tent" /></template>
<style>
.hcadwabkv {
  d: path("M2.5 20.5L12 5l9.5 15.5Zm8-17L12 5l1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vs5j3vbrx {
  d: path("M8.5 20.5L12 12l3.5 8.5");
}

</style>
