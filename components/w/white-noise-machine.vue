<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atr_hlgmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:white-noise-machine" /></template>
<style>
.atr_hlgmd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 15a8 2.5 0 0 1 16 0v3a8 2.5 0 0 1-16 0Zm5.25-6.75a4 4 0 0 1 5.5 0m-8-2.5a7.5 7.5 0 0 1 10.5 0");
}

</style>
