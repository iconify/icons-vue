<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy1t89nms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speed-radar" /></template>
<style>
.jy1t89nms {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 5h7a3 3 0 0 1 3 3a3 3 0 0 1-3 3h-7a3 3 0 0 1-3-3a3 3 0 0 1 3-3m3 6l1.5 8.5h3.5L18 11M6.25 6a3 3 0 0 0 0 4M4 4a6 6 0 0 0 0 8");
}

</style>
