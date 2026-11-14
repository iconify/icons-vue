<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy1irvbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-ferry" /></template>
<style>
.jy1irvbot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12.5h19l-2.5 5H5Zm3.5 0V8a1 1 0 0 1 1-1h8l2.5 5.5m-7-9.5zA1.5 1.5 0 0 1 12 4.5v1A1.5 1.5 0 0 1 10.5 7A1.5 1.5 0 0 1 9 5.5v-1A1.5 1.5 0 0 1 10.5 3M3 21q2.25-1.5 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
