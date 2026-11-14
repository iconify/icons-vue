<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbglz4y7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:net-force" /></template>
<style>
.tbglz4y7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17h18m-4-4l4 4l-4 4M3 6h8M8.5 3.5L11 6L8.5 8.5M21 6h-5.5M18 3.5L15.5 6L18 8.5");
}

</style>
