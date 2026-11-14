<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbflvth7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swim-lap-counter" /></template>
<style>
.wbflvth7x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0m6 0a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0m6 0a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0m-12 8q2.25-1.5 4.5 0t4.5 0m4 .5a2.75 2.75 0 0 1 5.5 0c0 2.25-5.5 3.5-5.5 6h5.75");
}

</style>
