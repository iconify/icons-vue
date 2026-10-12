<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m88w2vb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shoe" /></template>
<style>
.m88w2vb-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 19.5h3.5L8 18.25h3.25L12 19.5h8.25a1 1 0 0 0 1-1.1c-.3-2.4-1.9-3.4-4.35-4.15l-5.9-1.5H8.75c-.75 0-1.25-.5-1.5-1.25h-3.5a1 1 0 0 0-1 1v6a1 1 0 0 0 1 1m8.5-6L11.5 15m3-.75l-.75 1.5");
}

</style>
