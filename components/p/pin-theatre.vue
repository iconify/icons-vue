<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skzstkb2u"/><path class="cu0o9rodz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-theatre" /></template>
<style>
.cu0o9rodz {
  d: path("M8.75 9.25a2 2 0 0 1-3.5 0m10.5 6h.01m2.99 0h.01M15.75 20a1.75 1.75 0 0 1 3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.skzstkb2u {
  d: path("M2.5 2.5q4.5 1.5 9 0V9a4.5 4.5 0 0 1-9 0ZM13 11.75q4.25 1.5 8.5 0v5.75a4.25 4 0 0 1-8.5 0Zm-7.75-5.5h.01m3.49 0h.01");
}

</style>
