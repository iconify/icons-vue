<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o8wal04ex"/><path class="h7z6y5q1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:priest-collar-sharp" /></template>
<style>
.h7z6y5q1j {
  d: path("M10.75 14.75h2.5v2.75h-2.5z");
}

.o8wal04ex {
  d: path("M2.75 21.25v-6.417L5.25 14L9 12.5l1.125 2.25h3.75L15 12.5l3.75 1.5l2.5.833v6.417Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
