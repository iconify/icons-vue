<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ol_uq6f3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pilates-reformer" /></template>
<style>
.ol_uq6f3b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15H21M7.375 9.5h6.25A1.375 1.375 0 0 1 15 10.875a1.375 1.375 0 0 1-1.375 1.375h-6.25A1.375 1.375 0 0 1 6 10.875A1.375 1.375 0 0 1 7.375 9.5M3.5 15v3M21 15v3m-3.5-3l2-8");
}

</style>
