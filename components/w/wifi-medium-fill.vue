<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i_1pqwbir"/><path class="chh9m8bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wifi-medium-fill" /></template>
<style>
.chh9m8bfh {
  fill: currentColor;
  d: path("M13 18C13 18.5523 12.5523 19 12 19C11.4477 19 11 18.5523 11 18C11 17.4477 11.4477 17 12 17C12.5523 17 13 17.4477 13 18Z");
  stroke: none;
}

.i_1pqwbir {
  d: path("M9.3333 15.0186C10.0667 14.3626 11.0161 14 12 14C12.9839 14 13.9333 14.3626 14.6667 15.0186M6.6667 12.0372C8.1334 10.7253 10.0322 10 12 10C13.9678 10 15.8666 10.7253 17.3333 12.0372");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
