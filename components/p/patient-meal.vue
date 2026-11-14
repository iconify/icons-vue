<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6ax1lbly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patient-meal" /></template>
<style>
.l6ax1lbly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17h19v2.5h-19Zm1-2c0-4.25 2.75-6.5 6.25-6.5S16 10.75 16 15Zm6.25-8.25h.01M17.5 11H21v4h-3.5Z");
}

</style>
