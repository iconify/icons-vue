<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mjraufbpq"/><path class="f925awy7d"/><path class="urf-do1-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:superscript-linear" /></template>
<style>
.f925awy7d {
  d: path("M13.5 8L3 22");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mjraufbpq {
  d: path("M3 8L13.5 22");
}

.urf-do1-a {
  d: path("M17 3.8461C17 2.8265 17.8954 2 19 2C20.1046 2 21 2.8265 21 3.8461C21 4.8656 20.5634 5.356 19.7915 6.2571L17 9H21");
}

</style>
