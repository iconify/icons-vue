<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w72z3uspp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:signal-quality" /></template>
<style>
.w72z3uspp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11C4.25 4.25 7.5 4.25 9 11s4.75 6.75 6.25 0S20 4.25 21.5 11m-6.75 7l2 2L21 15.75");
}

</style>
