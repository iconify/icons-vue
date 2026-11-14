<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="px4kg0b4d"/><path class="zwqvjkbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sample-cup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.px4kg0b4d {
  d: path("M5 8h14l-1 11a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 19Zm.75-3.5h12.5A1.75 1.75 0 0 1 20 6.25A1.75 1.75 0 0 1 18.25 8H5.75A1.75 1.75 0 0 1 4 6.25A1.75 1.75 0 0 1 5.75 4.5");
}

.zwqvjkbdv {
  d: path("M10 11.5h4a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 15v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
