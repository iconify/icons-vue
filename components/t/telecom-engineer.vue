<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp46gacws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:telecom-engineer" /></template>
<style>
.tp46gacws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 7.5h11m-9.25 0a3.75 3.75 0 0 1 7.5 0m-7 0V9a3.25 3.25 0 0 0 6.5 0V7.5M3 20.5C3 17 6.25 15 10.5 15c1.505 0 2.885.251 4.039.73M15 21l3-3m3.75-1.5a2.25 2.25 0 1 1-2.25-2.25");
}

</style>
