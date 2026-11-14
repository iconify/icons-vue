<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q65b67b2p"/><path class="kj1hdbche"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:walker" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj1hdbche {
  fill: currentColor;
  d: path("M5 4h2a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 7 7H5a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 5 4");
}

.q65b67b2p {
  d: path("M4.5 5.5H17m-11 0l-2 16m11.5-16L18 19M5 13h11.75m.25 7.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
