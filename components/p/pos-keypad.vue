<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1giyo3pl"/><path class="zyfgcgbkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-keypad" /></template>
<style>
.b1giyo3pl {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyfgcgbkb {
  d: path("M17.125 5.5zA1.375 1.375 0 0 1 18.5 6.875v10.25a1.375 1.375 0 0 1-1.375 1.375a1.375 1.375 0 0 1-1.375-1.375V6.875A1.375 1.375 0 0 1 17.125 5.5M6.25 6.75h.01m3.24 0h.01m3.24 0h.01M6.25 12h.01m3.24 0h.01m3.24 0h.01m-6.51 5.25h.01m3.24 0h.01m3.24 0h.01");
}

</style>
