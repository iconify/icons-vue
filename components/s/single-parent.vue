<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v83gm5eok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:single-parent" /></template>
<style>
.v83gm5eok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0M3 21.5v-5.25a4.5 4.5 0 0 1 9 0v5.25M15.75 11a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1 10.5v-2.75a3 3 0 0 1 6 0v2.75");
}

</style>
