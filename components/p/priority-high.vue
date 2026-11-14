<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ihvl-zl6o"/><path class="yrfw9q2nk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:priority-high" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ihvl-zl6o {
  d: path("M5.5 10L12 3.5l6.5 6.5");
}

.yrfw9q2nk {
  d: path("M5.5 15.5L12 9l6.5 6.5m-11 5h9");
}

</style>
