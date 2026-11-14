<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ows-mlbmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:nuclear-energy" /></template>
<style>
.ows-mlbmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 12h5a9 9 0 0 0-4.5-7.75L14 8.5a4 4 0 0 1 2 3.5Zm-8 0H3a9 9 0 0 1 4.5-7.75L10 8.5A4 4 0 0 0 8 12Zm2 3.5l-2.5 4.25a9 9 0 0 0 9 0L14 15.5a4 4 0 0 1-4 0Zm.75-3.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

</style>
