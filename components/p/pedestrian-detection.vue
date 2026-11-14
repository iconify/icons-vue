<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ewy6-9bhw"/><path class="a_gfszb3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pedestrian-detection" /></template>
<style>
.a_gfszb3b {
  d: path("M9 11.25L11.75 10l2.5 2");
}

.ewy6-9bhw {
  d: path("M3.5 8V6A2.5 2.5 0 0 1 6 3.5h2m8 0h2A2.5 2.5 0 0 1 20.5 6v2m0 8v2a2.5 2.5 0 0 1-2.5 2.5h-2m-8 0H6A2.5 2.5 0 0 1 3.5 18v-2m8-8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m.75 2.5L11 13.25L13 15v2.75m-2-4.5L9.75 15.5L8 17.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
