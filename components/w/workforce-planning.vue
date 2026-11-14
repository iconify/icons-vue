<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o6jqk4b8x"/><path class="xe0fnkmly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:workforce-planning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o6jqk4b8x {
  d: path("M2.5 16.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m10.5 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

.xe0fnkmly {
  d: path("M6.125 9.5h1.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-1.25a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 6.125 9.5m10.5 0h1.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-1.25a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 16.625 9.5M11 14.5h2M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
