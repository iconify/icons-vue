<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d01fn-0qd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-home-ready" /></template>
<style>
.d01fn-0qd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 18v-1.5c-1.75-1-2.5-2.5-2.5-4a5 5 0 0 1 10 0c0 1.5-.75 3-2.5 4V18Zm.75 2.75h3.5M7.018 6.563a7.75 7.75 0 0 1 9.964 0M5.977 3.899a10.5 10.5 0 0 1 12.046 0");
}

</style>
