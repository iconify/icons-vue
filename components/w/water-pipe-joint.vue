<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0xn62b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:water-pipe-joint" /></template>
<style>
.b0xn62b7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 6h1.5a1.75 1.75 0 0 1 1.75 1.75v8.5A1.75 1.75 0 0 1 12.75 18h-1.5a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 11.25 6M2.5 9h7m-7 6h7m5-6h7m-7 6h7");
}

</style>
