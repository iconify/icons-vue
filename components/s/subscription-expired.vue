<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ctq0t5yes"/><path class="vhrqxgm1n"/><path class="mpvavabzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:subscription-expired" /></template>
<style>
.ctq0t5yes {
  d: path("M5.938 8.5A7 7 0 0 1 19 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpvavabzv {
  d: path("M7.5 14.5L5 12l-2.5 2.5M10 10l4 4m0-4l-4 4");
}

.vhrqxgm1n {
  d: path("M16.5 9.5L19 12l2.5-2.5m-3.438 6A7 7 0 0 1 5 12");
}

</style>
