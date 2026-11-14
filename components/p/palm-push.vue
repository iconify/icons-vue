<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts56y5rfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:palm-push" /></template>
<style>
.ts56y5rfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8v7.5A5.5 5.5 0 0 0 8 21h1a5.5 5.5 0 0 0 5.5-5.5V7m-9-2v7m3-8.5V12m3-7.5V12m6 0h4.25M19.5 9.75L21.75 12l-2.25 2.25");
}

</style>
