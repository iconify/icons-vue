<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csxkp-f3z"/><path class="qm1bgtblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:usb-stick-lock" /></template>
<style>
.csxkp-f3z {
  d: path("M10.5 9h3a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-3A3.5 3.5 0 0 1 7 18v-5.5A3.5 3.5 0 0 1 10.5 9m-.25-6.5h3.5a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 13.75 9h-3.5A1.75 1.75 0 0 1 8.5 7.25v-3a1.75 1.75 0 0 1 1.75-1.75m.5 3.25h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qm1bgtblj {
  d: path("M11.25 14.5h1.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-1.5a1.5 1.5 0 0 1-1.5-1.5V16a1.5 1.5 0 0 1 1.5-1.5m-.5 0v-1a1.25 1.25 0 0 1 2.5 0v1");
}

</style>
