<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0-lqcb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mouse-scroll" /></template>
<style>
.y0-lqcb1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3za5.5 5.5 0 0 1 5.5 5.5v7A5.5 5.5 0 0 1 9 21a5.5 5.5 0 0 1-5.5-5.5v-7A5.5 5.5 0 0 1 9 3m0 3.5v3M17.5 8L19 6.5L20.5 8m-3 5l1.5 1.5l1.5-1.5");
}

</style>
