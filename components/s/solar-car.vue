<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f8w58tb4x"/><path class="dwa-zub6y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:solar-car" /></template>
<style>
.dwa-zub6y {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8.5 3.5h7A1.5 1.5 0 0 1 17 5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 5a1.5 1.5 0 0 1 1.5-1.5m3.5 3v3");
}

.f8w58tb4x {
  d: path("M5 18H2.5v-3.5A1.5 1.5 0 0 1 4 13h2.5L9 9.5h6l2.5 3.5H20a1.5 1.5 0 0 1 1.5 1.5V18H19M9 18h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
