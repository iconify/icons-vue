<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rhd8faceg"/><path class="ztnmn8b6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:specimen-jar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rhd8faceg {
  d: path("M8 2.5h8A1.5 1.5 0 0 1 17.5 4A1.5 1.5 0 0 1 16 5.5H8A1.5 1.5 0 0 1 6.5 4A1.5 1.5 0 0 1 8 2.5m-.5 3V7c-2 .5-3 2-3 4v8A2.5 2.5 0 0 0 7 21.5h10a2.5 2.5 0 0 0 2.5-2.5v-8c0-2-1-3.5-3-4V5.5M4.5 12h15");
}

.ztnmn8b6p {
  d: path("M8.5 16.75c1.5-2.25 4.5-2.25 6 0l1.5-1.5v3l-1.5-1.5C13 19 10 19 8.5 16.75");
}

</style>
