<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dos345tfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-ice" /></template>
<style>
.dos345tfr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19M4.079 10.569l.668-2.227a1.5 1.5 0 0 1 1.112-1.033l2.096-.466A1.5 1.5 0 0 1 9.76 8.061l.449 2.692a1.5 1.5 0 0 1-1.48 1.747H5.516a1.5 1.5 0 0 1-1.437-1.931m10.171.181l.411-.959a1.5 1.5 0 0 1 1.193-.898l1.971-.246a1.5 1.5 0 0 1 1.591.962l.334.891a1.48 1.48 0 0 1-1.386 2h-2.96a1.255 1.255 0 0 1-1.154-1.75M4.5 16.5q2-1.5 4 0t4 0t4 0t3 .5");
}

</style>
