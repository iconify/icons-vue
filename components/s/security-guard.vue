<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofh5zjrqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:security-guard" /></template>
<style>
.ofh5zjrqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.158 5.526l.5-1.5A1.5 1.5 0 0 1 8.081 3h7.838a1.5 1.5 0 0 1 1.423 1.026l.5 1.5A1.5 1.5 0 0 1 16.419 7.5H7.581a1.5 1.5 0 0 1-1.423-1.974M8.5 7.5V10a3.5 3.5 0 0 0 7 0V7.5m-11 14c0-3 3.25-5 7.5-5s7.5 2 7.5 5");
}

</style>
