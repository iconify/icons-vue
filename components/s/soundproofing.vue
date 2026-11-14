<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="g_wmc9bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soundproofing" /></template>
<style>
.g_wmc9bjh {
  d: path("m5 7.75l1.75-2.5l1.75 2.5l1.75-2.5L12 7.75l1.75-2.5l1.75 2.5l1.75-2.5L19 7.75M6.75 13l1.75-2.5l1.75 2.5L12 10.5l1.75 2.5l1.75-2.5l1.75 2.5M5 18.25l1.75-2.5l1.75 2.5l1.75-2.5l1.75 2.5l1.75-2.5l1.75 2.5l1.75-2.5l1.75 2.5");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
