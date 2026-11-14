<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2n4e6bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:notification-follow" /></template>
<style>
.f2n4e6bts {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.299 19.5H3.5c-.6 0-1-.4-1-1c0-3 3-5.25 7-5.25c1.459 0 2.785.299 3.881.825M5.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm9.25 12.75L15.5 18v-1.25a2.5 2.5 0 0 1 5 0V18l.75 1.25Zm2.5 2.75h1.5");
}

</style>
