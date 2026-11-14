<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka32rqbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:transform" /></template>
<style>
.ka32rqbfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 2.5h1A1.5 1.5 0 0 1 6.5 4v1A1.5 1.5 0 0 1 5 6.5H4A1.5 1.5 0 0 1 2.5 5V4A1.5 1.5 0 0 1 4 2.5m15 0h1A1.5 1.5 0 0 1 21.5 4v1A1.5 1.5 0 0 1 20 6.5h-1A1.5 1.5 0 0 1 17.5 5V4A1.5 1.5 0 0 1 19 2.5m-15 15h1A1.5 1.5 0 0 1 6.5 19v1A1.5 1.5 0 0 1 5 21.5H4A1.5 1.5 0 0 1 2.5 20v-1A1.5 1.5 0 0 1 4 17.5m15 0h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5M8.5 4.5h7m-7 15h7m-11-11v7m15-7v7");
}

</style>
