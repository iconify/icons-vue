<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e77xs0bsj"/><path class="gaq37x0di"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-journey" /></template>
<style>
.e77xs0bsj {
  d: path("M17 13.5S13 10 13 7a4.25 4.25 0 0 1 8.25 0c0 3-4.25 6.5-4.25 6.5");
}

.gaq37x0di {
  d: path("M15.5 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M3 20.5h.01M6 20h.01m2.74-1.25h.01m1.24-2.5h.01m-1.51-2.5h.01M7 11.25h.01M8 8.75h.01m2.24-1.5h.01M17 16.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
