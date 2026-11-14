<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6579mlej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mangrove-tree" /></template>
<style>
.m6579mlej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7a8 4.5 0 1 0 16 0A8 4.5 0 1 0 4 7m8 4.5V14m0 0c-4 0-6.5 2.5-7.5 7m7.5-7c-1.5 1.5-3 4-3 7m3-7c1.5 1.5 3 4 3 7m-3-7c4 0 6.5 2.5 7.5 7m-17 0h19");
}

</style>
