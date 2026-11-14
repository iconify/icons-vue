<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr7b6sb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:people-line" /></template>
<style>
.kr7b6sb7b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-1.25 14v-5a3.75 3.75 0 0 1 7.5 0v5M9 9a2 2 0 1 0 4 0a2 2 0 1 0-4 0M7.75 20.5V17A3.25 3.25 0 0 1 11 13.75M3.25 11.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-.75 9v-2A2.5 2.5 0 0 1 5 16");
}

</style>
