<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="by5mge13t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rating-stars" /></template>
<style>
.by5mge13t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3.25l1.469 2.727l3.049.555l-2.14 2.241l.414 3.07L12 10.5l-2.792 1.343l.414-3.07l-2.14-2.241l3.049-.555ZM6.5 12.5l1.323 2.43l2.719.507l-1.902 2.008l.358 2.743L6.5 19l-2.498 1.188l.358-2.743l-1.902-2.008l2.719-.507Zm11 0l1.323 2.43l2.719.507l-1.902 2.008l.358 2.743L17.5 19l-2.498 1.188l.358-2.743l-1.902-2.008l2.719-.507Z");
}

</style>
