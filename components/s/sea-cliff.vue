<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zus9ejk_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sea-cliff" /></template>
<style>
.zus9ejk_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h6l2 5l-1 4l2 5.5h-9Zm12 14.5q1.75-1.5 3.5 0t3.5 0M15 14.5q1.75-1.5 3.5 0t3 .25");
}

</style>
