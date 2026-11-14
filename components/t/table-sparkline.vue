<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mrn8bfgyq"/><path class="npt6qybnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:table-sparkline" /></template>
<style>
.mrn8bfgyq {
  d: path("M2.5 2.5h19v19h-19Zm0 6.5h19m-19 6h19m-16-9.25h4M5.5 12h4m-4 6.25h4");
}

.npt6qybnt {
  d: path("m12.5 6.75l2-2l1.5 1.5l2.5-1.5m-6 8l2-1.25l1.5 1.25L18.5 11m-6 7l2 1.25l1.5-1.5L18.5 19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
