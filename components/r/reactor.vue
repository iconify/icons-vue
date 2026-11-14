<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3lznnaxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:reactor" /></template>
<style>
.n3lznnaxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21.5q3-6.5 2-12h9q-1 5.5 2 12ZM8 6.5a2.25 2.25 0 0 1 3-3a2.5 2.5 0 0 1 4.5 1a2 2 0 0 1 .5 2Z");
}

</style>
