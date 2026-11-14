<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5frkzbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:swimming-lesson" /></template>
<style>
.v5frkzbek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0M3 14c1.5-1.5 2.5-1.5 4 0l4.5-5l5.5 2M2.5 18q3-2.25 6 0t6 0t6 0");
}

</style>
