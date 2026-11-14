<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixsqm055j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-melt-pavement" /></template>
<style>
.ixsqm055j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 21.5l5-10m8 0l5 10m-9-7.75v7M9 15.5l6 3.5m-6 0l6-3.5M9.5 9c-1.25-1.25 1.25-2.75 0-4s1.25-2 0-2.5m5 6.5c-1.25-1.25 1.25-2.75 0-4s1.25-2 0-2.5");
}

</style>
