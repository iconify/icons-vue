<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="ci8iaszfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:radiation-monitor" /></template>
<style>
.ci8iaszfx {
  d: path("M9 12H6a6 6 0 0 1 3-5.25l1.5 2.75A3 3 0 0 0 9 12m4.5-2.5L15 6.75A6 6 0 0 1 18 12h-3a3 3 0 0 0-1.5-2.5m0 5l1.5 2.75a6 6 0 0 1-6 0l1.5-2.75a3 3 0 0 0 3 0M12 12h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oy9aotbsd {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
