<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ittbotbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shingle-beach" /></template>
<style>
.ittbotbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5a3.75 3 0 1 0 7.5 0a3.75 3 0 1 0-7.5 0m10.5.25a4.25 3 0 1 0 8.5 0a4.25 3 0 1 0-8.5 0M8.5 11a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0M3 5q2.25-1.25 4.5 0T12 5t4.5 0T21 5");
}

</style>
