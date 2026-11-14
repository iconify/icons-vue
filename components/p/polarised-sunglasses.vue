<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eribl-2gq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:polarised-sunglasses" /></template>
<style>
.eribl-2gq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 9h1.5a3.25 3.25 0 0 1 3.25 3.25a3.25 3.25 0 0 1-3.25 3.25h-1.5a3.25 3.25 0 0 1-3.25-3.25A3.25 3.25 0 0 1 5.75 9m11 0h1.5a3.25 3.25 0 0 1 3.25 3.25a3.25 3.25 0 0 1-3.25 3.25h-1.5a3.25 3.25 0 0 1-3.25-3.25A3.25 3.25 0 0 1 16.75 9m-6.25 2q1.5-1.5 3 0M5 13.5l3-3m8 3l3-3");
}

</style>
