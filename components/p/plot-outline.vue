<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uwivq1yig"/><path class="w3slhhkon"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plot-outline" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uwivq1yig {
  d: path("M7 2.5h6.5l6 6V19a2.5 2.5 0 0 1-2.5 2.5H7A2.5 2.5 0 0 1 4.5 19V5A2.5 2.5 0 0 1 7 2.5Z");
}

.w3slhhkon {
  d: path("M13.5 2.5v4a2 2 0 0 0 2 2h4M7.25 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm6.25-3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM10 16.25l3.75-2M8 7h2.75");
}

</style>
