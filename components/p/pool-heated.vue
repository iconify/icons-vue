<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be2gyeb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pool-heated" /></template>
<style>
.be2gyeb1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5q2.25-1.5 4.75 0Q9.5 17 12 15.5q2.25-1.5 4.75 0q2.25 1.5 4.75 0M2.5 20q2.25-1.5 4.75 0Q9.5 21.5 12 20q2.25-1.5 4.75 0q2.25 1.5 4.75 0M8 11C7 9.75 9 8.25 8 7c-.5-.75-.25-1.5 0-2m4 6c-1-1.25 1-2.75 0-4c-.5-.75-.25-1.5 0-2m4 6c-1-1.25 1-2.75 0-4c-.5-.75-.25-1.5 0-2");
}

</style>
