<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwf48b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ship-captain" /></template>
<style>
.rlwf48b0v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 5c0-1.5 15-1.5 15 0L17 8H7ZM8 8v2.5a4 4 0 0 0 8 0V8M4.5 21.5c0-2.463 3.155-4.198 7.312-4.249M15.75 18a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M18 14.5v7M14.5 18h7");
}

</style>
