<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5q4ve1cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reservation" /></template>
<style>
.r5q4ve1cg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.58 16.05L8.17 6.7q.33-1.2 1.58-1.2H15q1.25 0 1.61 1.2l2.78 9.35q.36 1.2-.89 1.2h-12q-1.25 0-.92-1.2m10.17-8.8l-2.75 10m-4.25-6h3.75m-9.75 6h18.5m-16.75 0v3m15-3v3");
}

</style>
