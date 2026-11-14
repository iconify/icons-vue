<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m41uptbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:warehouse-safety-sign" /></template>
<style>
.m41uptbil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3.5h9A3.5 3.5 0 0 1 20 7v7a3.5 3.5 0 0 1-3.5 3.5h-9A3.5 3.5 0 0 1 4 14V7a3.5 3.5 0 0 1 3.5-3.5m4.5 14V21m0-14v6m0 3.5h.01");
}

</style>
