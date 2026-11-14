<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h209ifmmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:solar-cell" /></template>
<style>
.h209ifmmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.16 17H3L7 3h14l-2.335 8.173M5 10h14m-5-7l-4 14m6 1a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm2-2v-2m0 6v2m-2-4h-2m6 0h2m-5.5-1.5l-1.25-1.25m4.25 4.25l1.25 1.25M19.5 16.5l1.25-1.25M16.5 19.5l-1.25 1.25");
}

</style>
