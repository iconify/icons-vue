<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iw1n1bcjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-pointing" /></template>
<style>
.iw1n1bcjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM8 8v6.5M5 21l3-6.5l3 6.5m-6.5-8L8 9h5.5L20 7");
}

</style>
