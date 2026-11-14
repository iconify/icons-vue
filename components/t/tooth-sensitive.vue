<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt02x7b1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-sensitive" /></template>
<style>
.dt02x7b1w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.96 16.943c.595-2.391.865-4.417 1.54-6.443c.75-2.5 1-5.25-.75-6.5c-1.5-1-3.75-.5-5.25 1C8 3.5 5.75 3 4.25 4c-1.75 1.25-1.5 4-.75 6.5c.75 2.25 1 4.5 1.75 7.25c.5 1.75 2 1.75 2.5 0l.75-3.5c.25-1 1.75-1 2 0l.75 3.5c.5 1.75 2 1.75 2.5 0l.013-.047M19.5 14.5l-3 3.5H20l-2.75 3.5");
}

</style>
