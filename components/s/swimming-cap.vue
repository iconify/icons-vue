<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iqjz3zbtx"/><path class="w45xhdc8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swimming-cap" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqjz3zbtx {
  d: path("M3.5 16c0-7.5 4-11.5 8.5-11.5s8.5 4 8.5 11.5c0 1.5-1 2.5-2.5 2.5H6c-1.5 0-2.5-1-2.5-2.5");
}

.w45xhdc8j {
  d: path("M7 9.5C9.5 8 14.5 8 17 9.5");
}

</style>
