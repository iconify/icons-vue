<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-vih6b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shirt-on-hanger" /></template>
<style>
.r-vih6b_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 9L4 11.5L5.5 15l2-1v7h9v-7l2 1l1.5-3.5L15.5 9q-3.5 2.5-7 0m1.75-4.5A1.75 1.75 0 1 1 12 6.25v1M8.5 9L12 7.25L15.5 9");
}

</style>
