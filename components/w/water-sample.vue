<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i9y4kpb3g"/><path class="pnskvqb1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-sample" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i9y4kpb3g {
  d: path("M10 2.5v5.25a7 7 0 1 0 4 0V2.5m-5.5 0h7");
}

.pnskvqb1f {
  d: path("M5 15c2.5-1.5 4.5 1.5 7 0s4.5 1.5 7 0");
}

</style>
