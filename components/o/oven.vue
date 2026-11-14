<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ohenukbqz"/><path class="fultev6oe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oven" /></template>
<style>
.fultev6oe {
  d: path("M8.25 11h7.5a1.75 1.75 0 0 1 1.75 1.75v3.5A1.75 1.75 0 0 1 15.75 18h-7.5a1.75 1.75 0 0 1-1.75-1.75v-3.5A1.75 1.75 0 0 1 8.25 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ohenukbqz {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3M13.5 7h.01M17 7h.01");
}

</style>
