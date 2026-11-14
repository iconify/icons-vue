<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2-5dobvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pool-depth-marker" /></template>
<style>
.m2-5dobvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 2.5v19m0-16h4.5m-4.5 4h4.5m-4.5 4h4.5M3 18.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
