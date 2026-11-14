<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j-5qa0bpe"/><path class="reyug-xyv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouth-open" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j-5qa0bpe {
  d: path("M2.5 12.5a9.5 7 0 1 0 19 0a9.5 7 0 1 0-19 0M3.75 9h16.5M9.5 5.75V9m5-3.25V9M4.25 16.5h15.5m-9.75 0v2.75m4-2.75v2.75");
}

.reyug-xyv {
  d: path("M8 16.5c0-3.75 8-3.75 8 0");
}

</style>
