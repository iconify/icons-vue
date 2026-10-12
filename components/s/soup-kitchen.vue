<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1wagz2wl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soup-kitchen" /></template>
<style>
.g1wagz2wl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 10.75h16a.75.75 0 0 1 .75.8A8.75 8.75 0 0 1 16 18.7v1.55a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1V18.7a8.75 8.75 0 0 1-4.75-7.15a.75.75 0 0 1 .75-.8m4.5-2.5c-.6-.6-.6-1.4 0-2s.6-1.4 0-2m3.5 4c-.6-.6-.6-1.4 0-2s.6-1.4 0-2m3.5 4c-.6-.6-.6-1.4 0-2s.6-1.4 0-2");
}

</style>
