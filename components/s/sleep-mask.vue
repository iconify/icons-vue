<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i2m35hb5y"/><path class="gjft2gz7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleep-mask" /></template>
<style>
.gjft2gz7m {
  d: path("M7.75 11.5q1.5 1.5 3 0m2.5 0q1.5 1.5 3 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2m35hb5y {
  d: path("M6.5 8.5c2.5-1.75 8.5-1.75 11 0c1.5 1 1.5 6.5 0 7.5c-2 1.5-4.25 1.25-5.5-.5c-1.25 1.75-3.5 2-5.5.5C5 15 5 9.5 6.5 8.5m-4 3.75h3m13 0h3");
}

</style>
