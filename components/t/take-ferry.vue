<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3zla7brl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:take-ferry" /></template>
<style>
.d3zla7brl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19l-3 5h-13Zm3.5 0v-4a1 1 0 0 1 1-1h8l3 5M10 3za1.5 1.5 0 0 1 1.5 1.5V5A1.5 1.5 0 0 1 10 6.5A1.5 1.5 0 0 1 8.5 5v-.5A1.5 1.5 0 0 1 10 3M3.5 21q2.75-1.5 5.5 0t5.5 0t5.5 0");
}

</style>
