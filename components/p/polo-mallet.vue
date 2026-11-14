<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoazcebzi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:polo-mallet" /></template>
<style>
.aoazcebzi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 17.5h8.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 21h-8.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M5.5 3L15 17.5m-12.5 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
