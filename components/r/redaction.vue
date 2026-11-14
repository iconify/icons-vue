<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uq4r9qq-h"/><path class="q9twa5b-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:redaction" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q9twa5b-q {
  fill: currentColor;
  d: path("M9.25 9.75h5.5A1.25 1.25 0 0 1 16 11a1.25 1.25 0 0 1-1.25 1.25h-5.5A1.25 1.25 0 0 1 8 11a1.25 1.25 0 0 1 1.25-1.25m0 5.25h2.5A1.25 1.25 0 0 1 13 16.25a1.25 1.25 0 0 1-1.25 1.25h-2.5A1.25 1.25 0 0 1 8 16.25A1.25 1.25 0 0 1 9.25 15");
}

.uq4r9qq-h {
  d: path("M8.875 2.5h6.25A4.375 4.375 0 0 1 19.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-6.25A4.375 4.375 0 0 1 4.5 17.125V6.875A4.375 4.375 0 0 1 8.875 2.5M8 6.5h8");
}

</style>
