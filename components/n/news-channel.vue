<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jsax5y56k"/><path class="yh6himb0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:news-channel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jsax5y56k {
  d: path("M6 7.5h12a3.5 3.5 0 0 1 3.5 3.5v6.5A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5V11A3.5 3.5 0 0 1 6 7.5M8.5 3L12 7.5L15.5 3");
}

.yh6himb0k {
  d: path("m12.61 12.402l.885.619a1.5 1.5 0 0 1 0 2.458l-.885.619a1.5 1.5 0 0 1-2.36-1.229v-1.238a1.5 1.5 0 0 1 2.36-1.229");
}

</style>
