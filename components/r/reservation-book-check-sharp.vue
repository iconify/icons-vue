<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crzbok2nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reservation-book-check-sharp" /></template>
<style>
.crzbok2nj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.58 16.05L8.17 6.7l.33-1.2h7.75l.36 1.2l2.78 9.35l.36 1.2H5.25zm10.17-8.8l-2.75 10m-4.25-6h3.75m-9.75 6h18.5m-16.75 0v3m15-3v3");
}

</style>
