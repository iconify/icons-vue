<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d1lrsckzw"/><path class="jr933wb2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-cash-pooling" /></template>
<style>
.d1lrsckzw {
  d: path("M6.75 16.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.jr933wb2x {
  d: path("M11.25 12h1.5a4.5 4.5 0 0 1 0 9h-1.5M12 2.5V9M9.5 6.5L12 9l2.5-2.5m-12 0l4 4m-2.75 0H6.5V7.75m15-1.25l-4 4m2.75 0H17.5V7.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
