<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4do6dbhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rancher" /></template>
<style>
.a4do6dbhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7.5Q4 10 12 10t9.5-2.5M8 9.75L8.75 4q1.5-1 3.25 0q1.75-1 3.25 0L16 9.75M9 10v1.5a3 3 0 0 0 6 0V10M4.5 21.5c0-2 3.25-3.75 7.5-3.75s7.5 1.75 7.5 3.75");
}

</style>
