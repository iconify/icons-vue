<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="etcan_mmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rss-plus" /></template>
<style>
.etcan_mmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13a6 6 0 0 1 6 6M5 7.5A11.5 11.5 0 0 1 16.5 19m-12.25-.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M18 3v6m-3-3h6");
}

</style>
