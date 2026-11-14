<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o42i3wbot"/><path class="t0ktyzgmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vine-tendril" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o42i3wbot {
  d: path("M3.5 21.5C3.5 13 8 4 14 4a5.5 5.5 0 0 1 0 11a3.5 3.5 0 0 1 0-7a2 2 0 0 1 0 4");
}

.t0ktyzgmb {
  d: path("M4 16.5c2-2 4.5-1.5 6 1c-2.5 1.5-4.5 1-6-1");
}

</style>
