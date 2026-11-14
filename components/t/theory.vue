<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0riuswsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:theory" /></template>
<style>
.j0riuswsa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-7 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m14 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M10.75 7.25l-4.5 8.5m7-8.5l4.5 8.5M7.5 18h9");
}

</style>
