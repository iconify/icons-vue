<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4mi5cahy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tulip-bloom-single" /></template>
<style>
.o4mi5cahy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 4l2.5 2.5l2.5-3l2.5 3L17 4v5A5 5 0 0 1 7 9Zm5 10v7.5m0-.5q-6-.5-6-6q5 1 6 6m0 0q6-.5 6-6q-5 1-6 6");
}

</style>
