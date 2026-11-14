<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ahmx_wb3g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-ball-classic" /></template>
<style>
.ahmx_wb3g {
  d: path("m12.915 9.204l1.489 1.145a1.5 1.5 0 0 1 .508 1.664l-.57 1.711a1.5 1.5 0 0 1-1.423 1.026h-1.838a1.5 1.5 0 0 1-1.423-1.026l-.57-1.711a1.5 1.5 0 0 1 .508-1.664l1.489-1.145a1.5 1.5 0 0 1 1.83 0M8.75 3L12 5l3.25-2m4.25 3.25l-.75 3.5l2.75 2.5m-1.75 5l-3.75.5L14.5 21m-5 0L8 17.75l-3.75-.5m-1.75-5l2.75-2.5l-.75-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
