<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pb38w8bqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seedling-transplant" /></template>
<style>
.pb38w8bqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15H14c0 3-3 5-6.5 5c-2.5 0-5-2-5-5M14 15h2.75M18 13.75h2.25A1.25 1.25 0 0 1 21.5 15a1.25 1.25 0 0 1-1.25 1.25H18A1.25 1.25 0 0 1 16.75 15A1.25 1.25 0 0 1 18 13.75M8.25 15V9m0 1c0-2.75-1.75-4.5-4.75-4.5c0 3 2 4.5 4.75 4.5m0-1C8.25 6 10 4 13 4c0 3-2 5-4.75 5");
}

</style>
