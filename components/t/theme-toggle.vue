<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gjfrbhz8c"/><path class="vcnv2mbii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:theme-toggle" /></template>
<style>
.gjfrbhz8c {
  d: path("M6.5 6h11a4 4 0 0 1 4 4v4a4 4 0 0 1-4 4h-11a4 4 0 0 1-4-4v-4a4 4 0 0 1 4-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vcnv2mbii {
  d: path("M17.25 9a3.25 3.25 0 1 0 1.5 5a2.75 2.75 0 0 1-1.5-5ZM8.5 12h.01");
}

</style>
