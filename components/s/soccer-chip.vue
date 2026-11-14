<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m3tj9wb-b"/><path class="q1w1xiban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:soccer-chip" /></template>
<style>
.m3tj9wb-b {
  d: path("M6.5 8a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.q1w1xiban {
  d: path("m12 5.5l2.25 1.75L13.5 10h-3l-.75-2.75Zm0 0v-3m2.25 4.75l3-1M13.5 10l1.75 2.5M10.5 10l-1.75 2.5m1-5.25l-3-1m-2 6.25q-1 3-1.25 8m15.75-8q1 3 1.25 8m-1.75-1.75l1.75 1.75l1.25-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
