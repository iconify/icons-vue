<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnnmlab-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shin-guards" /></template>
<style>
.lnnmlab-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5q3-2.5 6 0l-.75 10q1.25 2.5.5 5.5h-5.5q-.75-3 .5-5.5Zm10 0q3-2.5 6 0l-.75 10q1.25 2.5.5 5.5h-5.5q-.75-3 .5-5.5Z");
}

</style>
