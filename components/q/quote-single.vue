<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgftlhlsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:quote-single" /></template>
<style>
.rgftlhlsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4h6v7c0 5-2.5 8-7 9.5L8.5 19c2.5-1.25 3.75-3 4-5.5H10a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2");
}

</style>
