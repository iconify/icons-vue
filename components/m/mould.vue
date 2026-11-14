<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o8u5jki1x"/><path class="k4p7ntbfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mould" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k4p7ntbfq {
  d: path("M8.25 9.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M14.5 12h.01m-4.01 4.5h.01");
}

.o8u5jki1x {
  d: path("M5.5 21V11c-2.5-.5-3-2.5-3-3.5c0-3 3.5-5 9.5-5s9.5 2 9.5 5c0 1-.5 3-3 3.5v10Z");
}

</style>
