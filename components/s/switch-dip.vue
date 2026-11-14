<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wvb4twqow"/><path class="vw5q7j4jo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:switch-dip" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vw5q7j4jo {
  d: path("M6.5 8.5H9v7H6.5Zm4.25 0h2.5v7h-2.5Zm4.25 0h2.5v7H15Z");
}

.wvb4twqow {
  d: path("M3 6h18v12H3Z");
}

</style>
