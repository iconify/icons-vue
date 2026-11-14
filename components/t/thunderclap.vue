<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i20bel1pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:thunderclap" /></template>
<style>
.i20bel1pn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.5h8.5a3.5 3.5 0 0 0 0-7A4.75 4.75 0 0 0 7 5a3.25 3.25 0 0 0 0 6.5m5.5 2.5L10 17.75h4l-2.5 3.75m7.428-8a8 8 0 0 1 0 8");
}

</style>
