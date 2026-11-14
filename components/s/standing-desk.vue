<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uufq-7vjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:standing-desk" /></template>
<style>
.uufq-7vjj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 7h9.5A1.5 1.5 0 0 1 15 8.5a1.5 1.5 0 0 1-1.5 1.5H4a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 4 7m-.5 14.5h4m-2 0V10M10 21.5h4m-2 0V10m5.25-3.75L19.5 4l2.25 2.25M19.5 4v16m-2.25-2.25L19.5 20l2.25-2.25");
}

</style>
