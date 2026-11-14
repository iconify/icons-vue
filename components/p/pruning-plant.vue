<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhjqyx8xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pruning-plant" /></template>
<style>
.jhjqyx8xe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 20.25V5.75m0 7.75Q2 13.5 2 10q3.5 0 3.5 3.5m0-5Q5.5 5 9 5q0 3.5-3.5 3.5m5.5 9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M14 16l6.75-11.5M18.5 16L11.75 4.5");
}

</style>
