<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpi3h1r9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shelf-label-missing" /></template>
<style>
.tpi3h1r9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.5h15.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 7H4.25A1.75 1.75 0 0 1 2.5 5.25v-1A1.75 1.75 0 0 1 4.25 2.5M5.5 11v-1A1.5 1.5 0 0 1 7 8.5h1.5m7 0H17a1.5 1.5 0 0 1 1.5 1.5v1m0 5.5V18a1.5 1.5 0 0 1-1.5 1.5h-1.5m-7 0H7A1.5 1.5 0 0 1 5.5 18v-1.5m5.5-8h2m-2 11h2M5.5 13v1.5m13-1.5v1.5");
}

</style>
