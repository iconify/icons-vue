<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xvmlh0bwf"/><path class="mjlqhrnwk"/><path class="pawdd_79e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:survey-results" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjlqhrnwk {
  d: path("M3.75 5.25L4.5 6l1.25-1.5");
}

.pawdd_79e {
  fill: currentColor;
  d: path("M10.75 4h9.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-9.5A1.25 1.25 0 0 1 9.5 5.25A1.25 1.25 0 0 1 10.75 4m0 6.75h4.5A1.25 1.25 0 0 1 16.5 12a1.25 1.25 0 0 1-1.25 1.25h-4.5A1.25 1.25 0 0 1 9.5 12a1.25 1.25 0 0 1 1.25-1.25m0 6.75h7A1.25 1.25 0 0 1 19 18.75A1.25 1.25 0 0 1 17.75 20h-7a1.25 1.25 0 0 1-1.25-1.25a1.25 1.25 0 0 1 1.25-1.25");
}

.xvmlh0bwf {
  d: path("M4.25 3h1A1.75 1.75 0 0 1 7 4.75v1A1.75 1.75 0 0 1 5.25 7.5h-1A1.75 1.75 0 0 1 2.5 5.75v-1A1.75 1.75 0 0 1 4.25 3m0 6.75h1A1.75 1.75 0 0 1 7 11.5v1a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 2.5 12.5v-1a1.75 1.75 0 0 1 1.75-1.75m0 6.75h1A1.75 1.75 0 0 1 7 18.25v1A1.75 1.75 0 0 1 5.25 21h-1a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
