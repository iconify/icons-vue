<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hu1206n3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seed-dispersal" /></template>
<style>
.hu1206n3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6q7-6 14 0m-7 4L5 6m7 4l7-4m-7-3v12.5m-1.75 3a1.75 3 0 1 0 3.5 0a1.75 3 0 1 0-3.5 0");
}

</style>
