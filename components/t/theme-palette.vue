<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="keqk6qb-y"/><path class="e7fumclkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:theme-palette" /></template>
<style>
.e7fumclkw {
  d: path("M6.5 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM8 7.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm5-.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM16.5 10a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.keqk6qb-y {
  d: path("M12 2.5a9.5 9.5 0 0 0 0 19c1.5 0 2.25-1 2-2.25s-.5-2 .5-2.75c.75-.5 1.5-.5 2.5-.5h1a3.5 3.5 0 0 0 3.5-3.5c0-5.5-4.25-10-9.5-10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
