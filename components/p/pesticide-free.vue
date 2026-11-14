<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn-ycdb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pesticide-free" /></template>
<style>
.yn-ycdb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5c0-9 6-15 15-15c0 9-6 15-15 15m0 0L10 10m8.5 3.5l3 5a3 3 0 0 1-6 0Z");
}

</style>
