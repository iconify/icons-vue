<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8uwz1n7s"/><path class="dg6oekbiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:member-tier" /></template>
<style>
.dg6oekbiq {
  d: path("M8.25 13.75L7 21h3l.75-6.25m5-1L17 21h-3l-.75-6.25m-1.25-9l.75 2L15 8l-1.5 1.5l.5 2.25l-2-1.25l-2 1.25l.5-2.25L9 8l2.25-.25Z");
}

.f8uwz1n7s {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
