<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gv7j58bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sleep-sound" /></template>
<style>
.gv7j58bfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.5a7.5 7.5 0 0 0 0 15a9 9 0 0 1 0-15m3 4a5 5 0 0 1 0 7m3.5-10a9 9 0 0 1 0 13");
}

</style>
