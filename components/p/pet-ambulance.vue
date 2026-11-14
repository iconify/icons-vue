<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6bvuqbol"/><path class="ftnf4ybrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-ambulance" /></template>
<style>
.ftnf4ybrk {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-7.75-6.5a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0m-.5-3.75h.01M9 8.25h.01m2.24.5h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x6bvuqbol {
  d: path("M2.5 17V7A1.5 1.5 0 0 1 4 5.5h11l6.5 6V17ZM8.75 3h1A1.25 1.25 0 0 1 11 4.25A1.25 1.25 0 0 1 9.75 5.5h-1A1.25 1.25 0 0 1 7.5 4.25A1.25 1.25 0 0 1 8.75 3");
}

</style>
