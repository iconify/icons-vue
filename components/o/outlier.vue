<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l8coymb2i"/><path class="p60c4uc3i"/><path class="vjo79vsth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:outlier" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l8coymb2i {
  fill: currentColor;
  d: path("M16.25 6.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.p60c4uc3i {
  d: path("M14.25 6.25a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

.vjo79vsth {
  fill: currentColor;
  d: path("M3.25 14a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M7 13a1.25 1.25 0 1 0 2.5 0A1.25 1.25 0 1 0 7 13m-2 4.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m3.75-.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0m-6 3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M7 20.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
