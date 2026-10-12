<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m11vljb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:medicine-spoon" /></template>
<style>
.m11vljb_r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.75h13q1.75 0 1.47 1.73l-1.69 10.54q-.28 1.73-2.03 1.73h-8.5q-1.75 0-2.03-1.73L4.03 8.48Q3.75 6.75 5.5 6.75m2 4H11M7.75 14h2.5m-2 3.25h3");
}

</style>
