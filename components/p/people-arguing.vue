<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkllv7bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:people-arguing" /></template>
<style>
.bkllv7bbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 15c0-2.25 1.75-4 4-4s4 1.75 4 4m4-9.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-1 9.75c0-2.25 1.75-4 4-4c2.111 0 3.782 1.54 3.98 3.589m-2.405 1.405l1.754 3.302a1.5 1.5 0 0 1-1.324 2.204h-3.51a1.5 1.5 0 0 1-1.324-2.204l1.754-3.302a1.5 1.5 0 0 1 2.65 0M17.75 17.25V18m0 1.75h.01");
}

</style>
