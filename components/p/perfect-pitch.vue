<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8_f1jboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:perfect-pitch" /></template>
<style>
.g8_f1jboi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3v7a4.5 4.5 0 0 0 9 0V3M10 14.5v7m4.5-1.75a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Zm4.5 0V13.5");
}

</style>
