<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfcvjvbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:skipping-stone" /></template>
<style>
.tfcvjvbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 7.5a3.25 2 0 1 0 6.5 0a3.25 2 0 1 0-6.5 0M3 14q3.25-8 6.5 0q2.5-7 4.25-3.5m-11.25 7q2.25-1.25 4.5 0t4.5 0t4.5 0t5.5 0");
}

</style>
