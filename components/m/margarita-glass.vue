<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x80qmxbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:margarita-glass" /></template>
<style>
.x80qmxbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h16c0 2.75-2.5 4-5 4c0 2.5-1 4.5-3 4.5s-3-2-3-4.5C6.5 8 4 6.75 4 4m8 8.5v8m-4 0h8");
}

</style>
