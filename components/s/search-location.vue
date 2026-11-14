<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ydwudw6zd"/><path class="jox80ybte"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:search-location" /></template>
<style>
.jox80ybte {
  d: path("M10.5 14s-2.75-2.25-2.75-4.25a2.75 2.75 0 0 1 5.5 0c0 2-2.75 4.25-2.75 4.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydwudw6zd {
  d: path("M3.5 10.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Zm12 5l5 5");
}

</style>
