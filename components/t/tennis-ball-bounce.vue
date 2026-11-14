<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m3tj9wb-b"/><path class="h_pvp91wc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tennis-ball-bounce" /></template>
<style>
.h_pvp91wc {
  d: path("M8.25 4c2 2 2 6 0 8m7.5-8c-2 2-2 6 0 8M4 21h16M6.5 15.5L8 17.75m9.5-2.25L16 17.75");
}

.m3tj9wb-b {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
