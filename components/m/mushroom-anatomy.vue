<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6k_pxbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mushroom-anatomy" /></template>
<style>
.f6k_pxbfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 11a9 8 0 0 1 18 0Zm6 0l-.5 8.5A1.5 1.5 0 0 0 10 21h4a1.5 1.5 0 0 0 1.5-1.5L15 11m-3-8v18");
}

</style>
