<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qtmpdsb2g"/><path class="i813f7b0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:policy-certificate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i813f7b0j {
  d: path("m12 6.75l2.5 1V9.5c0 1.5-1.1 2.4-2.5 3c-1.4-.6-2.5-1.5-2.5-3V7.75ZM10 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1 1.75l-.75 2m2.75-2l.75 2");
}

.qtmpdsb2g {
  d: path("M6 4h12a3.5 3.5 0 0 1 3.5 3.5V13a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 13V7.5A3.5 3.5 0 0 1 6 4");
}

</style>
