<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1wn661ba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:non-compete" /></template>
<style>
.c1wn661ba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.75 3h1a1.75 1.75 0 0 1 1.75 1.75v15a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 16 19.75v-15A1.75 1.75 0 0 1 17.75 3M16 9l4.5-4M16 14.5l4.5-4M16 20l4.5-4M7 4.5H3.5v15H7M5.5 12h7M10 9.5l2.5 2.5l-2.5 2.5");
}

</style>
