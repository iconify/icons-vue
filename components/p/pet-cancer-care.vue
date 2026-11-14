<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avor5-bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-cancer-care" /></template>
<style>
.avor5-bmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 17l4.75-6.75c1-1.5 2-2.5 2-3.75a4 4 0 0 0-8 0c0 1.25 1 2.25 2 3.75L12.25 17m6 4C16.5 19.75 15 18.5 15 16.75a1.75 1.75 0 0 1 3.25-1a1.75 1.75 0 0 1 3.25 1c0 1.75-1.5 3-3.25 4.25Z");
}

</style>
