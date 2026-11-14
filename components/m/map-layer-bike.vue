<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xbd00hfzg"/><path class="rca2vpbtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-layer-bike" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rca2vpbtx {
  d: path("M8.481 15h1.636a1.5 1.5 0 0 0 1.312-.772l2.083-3.75a1.5 1.5 0 0 0-1.311-2.228h-2.192a1.5 1.5 0 0 0-1.39.934l-1.527 3.75A1.5 1.5 0 0 0 8.481 15m9.269 0l-3-6.75V5.5h2.75M9 8.25L8.5 5.5M7 5.5h3");
}

.xbd00hfzg {
  d: path("M2.5 15a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M14 15a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

</style>
