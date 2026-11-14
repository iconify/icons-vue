<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kkdql4bcp"/><path class="w7iy3qb8j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-rates-board" /></template>
<style>
.kkdql4bcp {
  d: path("M2.5 2.5h19v14h-19Zm9.5 14v5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w7iy3qb8j {
  d: path("M6 13.75v-8.5h2.5a2.5 2.5 0 0 1 0 5H6M17.5 7.5c0-.75-.75-1.25-1.75-1.25S14 6.75 14 7.75c0 2 3.5 1.25 3.5 3.5c0 1-.75 1.5-1.75 1.5S14 12.25 14 11.5m1.75-6.25v8.5");
}

</style>
