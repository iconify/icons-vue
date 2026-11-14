<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7saox1pc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-intern" /></template>
<style>
.c7saox1pc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20c0-2.75 2.9-4.75 6.5-4.75s6.5 2 6.5 4.75c0 .6-.4 1-1 1h-11c-.6 0-1-.4-1-1M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m10.893.25h1.714a1.5 1.5 0 0 1 1.494 1.636l-.227 2.5A1.5 1.5 0 0 1 17.63 14h-1.26a1.5 1.5 0 0 1-1.494-1.364l-.227-2.5A1.5 1.5 0 0 1 16.143 8.5m3.357 1h.75a1.5 1.5 0 0 1 0 3h-1M16 4.25v2m2-2v2");
}

</style>
