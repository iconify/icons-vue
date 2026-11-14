<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aavz8ozbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meter-reader" /></template>
<style>
.aavz8ozbw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0M8 9l2.75-2.75m5 6.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-2.25 9c0-2.5 2-4 4.5-4s4 1.5 4 4");
}

</style>
