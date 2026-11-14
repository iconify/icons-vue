<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d09u08isj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:store-occupancy" /></template>
<style>
.d09u08isj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M2.5 20.5c0-4 2.5-6 6-6c1.273 0 2.414.265 3.351.794M13 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0m1.25 11l.75-2.75h6l.75 2.75M15 17v4.75h6V17m-6.75 0h7.5");
}

</style>
