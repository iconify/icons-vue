<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g986pacge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-cuddle" /></template>
<style>
.g986pacge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h18c0 4.5-4 7.5-9 7.5s-9-3-9-7.5Zm2.5 0V5.5l2.5 2l2.5-2v3c4-.5 7 1.5 8 4.5m-.75-6c-1.25-.75-2.25-1.75-2.25-2.75a1.125 1.125 0 0 1 2.25 0a1.125 1.125 0 0 1 2.25 0c0 1-1 2-2.25 2.75Z");
}

</style>
