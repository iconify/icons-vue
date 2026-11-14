<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="na1vcjsqs"/><path class="bcwxzk24p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-phone" /></template>
<style>
.bcwxzk24p {
  fill: currentColor;
  d: path("M10.25 16.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.na1vcjsqs {
  d: path("M3 9V8c0-3 3.5-4.5 9-4.5S21 5 21 8v1h-4.5V7.5h-9V9Zm5.813 2.75h6.374a2.625 2.625 0 0 1 2.455 1.696l1.513 4A2.625 2.625 0 0 1 16.7 21H7.3a2.625 2.625 0 0 1-2.455-3.554l1.513-4a2.625 2.625 0 0 1 2.455-1.696");
}

</style>
