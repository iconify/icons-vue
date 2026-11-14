<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a3adxzbhy"/><path class="kwbehj53b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:retractable-leash" /></template>
<style>
.a3adxzbhy {
  d: path("M2.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0m11 0h3M19 9za2.5 2.5 0 0 1 2.5 2.5v1A2.5 2.5 0 0 1 19 15a2.5 2.5 0 0 1-2.5-2.5v-1A2.5 2.5 0 0 1 19 9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kwbehj53b {
  d: path("M6.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
