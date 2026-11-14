<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkcfwsc9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ph-scale" /></template>
<style>
.lkcfwsc9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12.75h13a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-13a3 3 0 0 1-3-3a3 3 0 0 1 3-3m3.25 0v6m6.5-6v6m-3.392-13.5h.284a1.307 1.307 0 0 1 1.108 2a1.474 1.474 0 0 1-2.5 0a1.307 1.307 0 0 1 1.108-2");
}

</style>
