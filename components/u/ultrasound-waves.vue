<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjga0bclz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ultrasound-waves" /></template>
<style>
.xjga0bclz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 2.5h1.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 12.75 6h-1.5A1.75 1.75 0 0 1 9.5 4.25a1.75 1.75 0 0 1 1.75-1.75m4.194 6.012a6.5 6.5 0 0 1-6.888 0m8.694 3.581a10.5 10.5 0 0 1-10.5 0m12.057 3.71a14.5 14.5 0 0 1-13.614 0");
}

</style>
