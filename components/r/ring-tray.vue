<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9bpdfbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ring-tray" /></template>
<style>
.f9bpdfbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 14h13.75a2.625 2.625 0 0 1 2.625 2.625v2.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-2.25A2.625 2.625 0 0 1 5.125 14M4.75 9.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m8 0a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M8 3.25za.72.72 0 0 1 .684.949L8.5 4.75a.527.527 0 0 1-1 0l-.184-.551A.72.72 0 0 1 8 3.25m8 0za.72.72 0 0 1 .684.949l-.184.551a.527.527 0 0 1-1 0l-.184-.551A.72.72 0 0 1 16 3.25");
}

</style>
