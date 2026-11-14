<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="evx_eac-p"/><path class="h-wdy8bwu"/><path class="ub1bmybzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prime-time" /></template>
<style>
.evx_eac-p {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v7.5A3.5 3.5 0 0 1 18 18H6a3.5 3.5 0 0 1-3.5-3.5V7A3.5 3.5 0 0 1 6 3.5M8.5 21h7");
}

.h-wdy8bwu {
  d: path("M7.5 10.75a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ub1bmybzl {
  d: path("M12 9v1.75l-1.5 1");
}

</style>
