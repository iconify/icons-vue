<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="omzehh8mk"/><path class="jday-ubyb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marker-circle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jday-ubyb {
  fill: currentColor;
  d: path("M9.5 9.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

.omzehh8mk {
  d: path("M4.5 9.75a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0m7.5 7.5v4.25");
}

</style>
