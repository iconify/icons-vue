<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wo-wu4b7y"/><path class="n16_xjzpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:walnut-tree" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n16_xjzpu {
  d: path("M9.75 10a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m2.75-2.75v5.5");
}

.wo-wu4b7y {
  d: path("M7 16c-3.5 0-4.5-4-2.5-6c-1-4 3-7.5 6.5-6.5c2.5-1.75 7-.5 7.5 3c3 1 3.25 6 1 7.5c-1 2-3.5 2-4.5 2Zm5 0v5.5");
}

</style>
