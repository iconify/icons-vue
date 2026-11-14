<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqj4zf6ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slider-value" /></template>
<style>
.hqj4zf6ke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3h9v7h-3L12 12l-1.5-2h-3Zm2 15a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM3 18h6.5m5 0H21");
}

</style>
