<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnyfrjb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-climbing" /></template>
<style>
.pnyfrjb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-2 6l5-1.25l5.5-2.25M11 9.75L9.5 14l4 2l-.013.12m-.199 1.789L13 20.5M9.5 14L6 17.5l.5 3.5m13-18.5v9.4M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

</style>
