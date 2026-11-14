<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oqvdhgjgc"/><path class="c29ae-t5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:visual-field-test" /></template>
<style>
.c29ae-t5s {
  d: path("M10 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7.5-.5a9.5 9.5 0 0 1 .465-2.936m.808-1.814a9.5 9.5 0 0 1 1.87-2.31M7.25 6.273a9.5 9.5 0 0 1 2.775-1.065m.489-.091a9.5 9.5 0 0 1 2.972 0m.489.091a9.5 9.5 0 0 1 2.775 1.065m1.607 1.167a9.5 9.5 0 0 1 1.87 2.31m.808 1.814A9.5 9.5 0 0 1 21.5 14.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqvdhgjgc {
  d: path("M5.5 15c2-3.5 11-3.5 13 0c-2 3.5-11 3.5-13 0");
}

</style>
