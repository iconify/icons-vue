<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5fidebdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:summer-sun" /></template>
<style>
.r5fidebdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m11.25 2.75l2 1m-2-6.5l2-1m-15.5 6.5l-2 1m2-6.5l-2-1m11.5 10.5l1 2m-6.5-2l-1 2m6.5-15.5l1-2m-6.5 2l-1-2");
}

</style>
