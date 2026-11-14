<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c39o4ab1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:steam-room-hotel" /></template>
<style>
.c39o4ab1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 14.5h15.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 19.75 18H4.25a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75M5.5 18v3m13-3v3M7 11.5C5.5 10 8.5 8 7 6.5s1.5-3 0-4m5 9c-1.5-1.5 1.5-3.5 0-5s1.5-3 0-4m5 9c-1.5-1.5 1.5-3.5 0-5s1.5-3 0-4");
}

</style>
