<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t5cg7g7nr"/><circle class="yjztigbem"/><path class="e3nk5wb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:racing-wheel" /></template>
<style>
.e3nk5wb7t {
  d: path("M5.25 12.5H10m4 0h4.75m-6.75 2v3m6.45-7h2.05a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75h-2.05m-12.9-4H3.5a.75.75 0 0 0-.75.75v2.5a.75.75 0 0 0 .75.75h2.05");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t5cg7g7nr {
  d: path("M7.47 17.5h9.06a6.75 6.75 0 1 0-9.06 0");
}

.yjztigbem {
  cx: 12px;
  cy: 12.5px;
  r: 2px;
}

</style>
