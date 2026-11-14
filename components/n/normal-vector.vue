<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tjd9_0e_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:normal-vector" /></template>
<style>
.tjd9_0e_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.25 17.25l1.3-1.671A1.5 1.5 0 0 1 7.734 15h9.916a1.394 1.394 0 0 1 1.1 2.25l-1.3 1.671a1.5 1.5 0 0 1-1.184.579H6.35a1.394 1.394 0 0 1-1.1-2.25m6.75 0V4M8.75 7.25L12 4l3.25 3.25");
}

</style>
