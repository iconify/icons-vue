<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h-csf7bdf"/><path class="klwtho-wi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tree-stump-axe" /></template>
<style>
.h-csf7bdf {
  d: path("M3.5 13a6.5 2 0 1 0 13 0a6.5 2 0 1 0-13 0Z");
}

.klwtho-wi {
  d: path("M3.5 13v6l-1 2h15l-1-2v-6m-9-1.75L9.5 7h2l1 4.25M11.5 7l9-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
