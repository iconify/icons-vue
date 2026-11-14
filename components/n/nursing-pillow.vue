<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcmm87btu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nursing-pillow" /></template>
<style>
.wcmm87btu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.75a9.5 8 0 1 0 12.5 0a2.5 2.5 0 0 0-4 3.25a3.5 3.5 0 1 1-4.5 0a2.5 2.5 0 0 0-4-3.25");
}

</style>
