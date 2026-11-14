<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m44wysm1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:polarisation" /></template>
<style>
.m44wysm1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12q1.5-5 3 0t2.75 0M11 3v18m3-18v18m4.75-15.5v13m-2-11l2-2l2 2m-4 9l2 2l2-2");
}

</style>
