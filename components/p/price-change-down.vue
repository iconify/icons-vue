<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cyymez1do"/><path class="gr8p5ub0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:price-change-down" /></template>
<style>
.cyymez1do {
  d: path("M8.5 4.5h11v15h-11l-5-7.5ZM8.25 12h.01M14 9v6");
}

.gr8p5ub0w {
  d: path("M11.75 13L14 15.25L16.25 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
