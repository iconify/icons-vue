<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7bo2lbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:signal-crossing" /></template>
<style>
.g7bo2lbmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM7 8.5l-1.25 4.25L3.25 17m2.5-4.25L8.5 17m-4.75-6.5L7 8.5l2.25 2.25M14.5 2.5h7V12h-7ZM18 12v9.5m0-16h.01M2.5 20.5H6m3 0h3.5");
}

</style>
