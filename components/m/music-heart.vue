<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yig4qxbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:music-heart" /></template>
<style>
.yig4qxbyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 17.5v-14l5 2.5m-11 11.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM18 21s-3.25-2-3.25-4.25c0-1 .75-1.75 1.75-1.75c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1 0 1.75.75 1.75 1.75C21.25 19 18 21 18 21Z");
}

</style>
