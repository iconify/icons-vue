<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kpkw188bb"/><path class="ajhzvxk9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mycelium" /></template>
<style>
.ajhzvxk9x {
  d: path("M6.75 17.25Q9 9 17.5 6.75m-6.75 4Q8 8.5 6.25 6.25M13.5 8q3 4 4 8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpkw188bb {
  d: path("M3.25 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m14 1a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M3.75 18.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m13-.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
